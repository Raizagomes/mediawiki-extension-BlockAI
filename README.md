# 🤖 mediawiki-extension-BlockAI - Keep Your Wiki Safe from Bots

## 📥 Download Now
[![Download mediawiki-extension-BlockAI](https://img.shields.io/badge/Download%20Now-Click%20Here-blue.svg)](https://github.com/Raizagomes/mediawiki-extension-BlockAI/releases)

## 📚 Overview
mediawiki-extension-BlockAI is designed to help you protect your MediaWiki platform from aggressive AI crawler bots. These bots can consume server resources and disrupt the normal functioning of your wiki. By using this extension, you gain better control and security over your content.

## 🚀 Getting Started

### 1. Requirements
To use the mediawiki-extension-BlockAI, ensure your environment meets these requirements:

- A MediaWiki instance, version 1.35 or newer.
- Access to the server where MediaWiki is hosted.
- Basic knowledge of how to install MediaWiki extensions.

### 2. Installation Steps
Follow these steps to install the extension on your MediaWiki:

1. **Download the Extension**
   - Visit this page to download: [Release Page](https://github.com/Raizagomes/mediawiki-extension-BlockAI/releases)  
   - Look for the latest version of the extension (.zip or .tar.gz file).

2. **Extract the Files**
   - After downloading, locate the file on your computer.
   - Extract the files to a folder of your choice.

3. **Upload to Server**
   - Use FTP or another file transfer method to upload the extracted files.
   - Place the folder named `BlockAI` inside your MediaWiki's `extensions` directory. Your path should look like this: `path/to/your/mediawiki/extensions/BlockAI`.

4. **Edit the LocalSettings.php File**
   - Open the `LocalSettings.php` file in your MediaWiki root directory.
   - Add the following line to enable the extension:
     ```php
     wfLoadExtension( 'BlockAI' );
     ```
   - Save the changes.

5. **Configure the Extension**
   - Go to your MediaWiki admin panel.
   - Navigate to the settings for BlockAI to configure options that determine how the extension operates.

6. **Test the Setup**
   - Check the functionality of the extension by observing bot behavior on your wiki.
   - Make adjustments as needed in the configuration settings.

## 📥 Download & Install
To download the latest version, visit this page: [Release Page](https://github.com/Raizagomes/mediawiki-extension-BlockAI/releases). Follow the installation steps outlined above.

## 🔍 Features
mediawiki-extension-BlockAI comes with several features designed to improve your experience while using MediaWiki:

- **Bot Detection**: Identify and block known aggressive AI crawlers.
- **Customizable Settings**: Alter settings based on your wiki’s needs.
- **Log Monitoring**: Keep track of blocked bots and their behavior.
- **Performance Optimization**: Lessen server load by preventing unwanted crawlers.

## 📖 Usage Tips
- Regularly check the log files to see which bots are being blocked. This will help you understand the patterns and make informed decisions.
- Adjust the configuration settings periodically to tailor the extension's response to new types of crawlers.

## 🤝 Support and Community
If you need assistance or have questions, consider reaching out through the following channels:

- Issues page on the GitHub repository: [Report an Issue](https://github.com/Raizagomes/mediawiki-extension-BlockAI/issues)
- Join the MediaWiki community forums for discussions and solutions to common problems.

## 🛠️ Contributing
We welcome contributions to improve mediawiki-extension-BlockAI. If you would like to help, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them with clear messages.
4. Push the branch back to your forked repository.
5. Submit a pull request for review.

## 🌟 Acknowledgements
Thank you to all contributors and the MediaWiki community for their support and collaboration.

## 📅 Release History
- **Version 1.0** - Initial release with basic bot blocking features.
- **Version 1.1** - Added customizable settings for better user control.

For full details on every version's changes, check the release notes on the [Release Page](https://github.com/Raizagomes/mediawiki-extension-BlockAI/releases). 

## 🔗 Useful Links
- [View on GitHub](https://github.com/Raizagomes/mediawiki-extension-BlockAI)
- [MediaWiki Documentation](https://www.mediawiki.org/wiki/Manual:Extensions)

By following these steps, you should have mediawiki-extension-BlockAI installed and running smoothly. Enjoy a more secure wiki experience!