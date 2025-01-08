# Automatic X.com Banner Updater

This repository automates updating the profile banner on your X.com (formerly Twitter) account daily using GitHub Actions. A Python script selects a random banner image from a predefined directory and updates your profile.

## Features
- Automatically updates your X.com profile banner daily. You can change the cron schedule in the GitHub Actions workflow file.
- Easy integration with GitHub Actions for seamless automation.
- Store and manage your banner images directly in the repository.

## Prerequisites
1. **X.com API Credentials**:
   - Sign up for a developer account at [X Developer Platform](https://developer.x.com/).
   - Create an app to obtain:
     - API Key
     - API Secret Key
     - Access Token
     - Access Token Secret

2. **GitHub Repository**:
   - Clone this repository or create your own GitHub repository.

## Directory Structure
```plaintext
my-github-repo/
│
├── .github/
│   └── workflows/
│       └── update_banner.yml  # GitHub Actions workflow file
│
├── banners/
│   ├── banner1.jpg            # Banner images for updates
│   ├── banner2.png
│   ├── banner3.jpeg
│   └── ...                    # Add as many banner images as needed
│
├── update_banner.py           # Python script for updating the banner
├── requirements.txt           # Dependencies for the Python script
├── .env                       # Environment variables for API credentials
└── README.md                  # This documentation
```

## Contact Me
Contact me on X.com at [x.com/aarongxa](https://x.com/aarongxa)
