# Thank You!

Thank you for your interest in Cozy Cloud! This kit provides essential information about the platform and its functionality.

# Synopsis

Cozy is a self-hosted extensible open source private cloud platform. Simplicity, user-friendliness, and flexibility are the cornerstones of Cozy's design and philosophy. As such, Cozy makes the personal server as simple as a smartphone. While Cozy offers native apps for managing common tasks like sharing files, synchronizing photos, managing calendars, and working with emails, the platform is built to aggregate, manage, and analyze personal data coming from multiple sources and services. This functionality has the potential to transform Cozy from a personal cloud server to a powerful platform for storing and working with personal data.

# What is Cozy?

Cozy is an open source self-hosted platform for managing personal data. Cozy's default suite of apps allows the user to store, share, and synchronize files and photos, keep tabs on appointments and contacts, and manage multiple email accounts. Third-party apps available through a dedicated app store can be used to extend Cozy's default functionality. This includes apps for reading RSS feeds, managing tasks, hosting a blog, etc.

Cozy's unique aspect is the ability to aggregate the user's personal data from various sources and services using connectors. For example, using a dedicated connector, Cozy can acquire and process banking data and help the user to manage their personal finances.

Simplicity and user-friendliness are core principles of Cozy's design. Thanks to approachable and lightweight interfaces, Cozy's apps are easy to master, and they practically have no learning curve. Maintenance tasks in Cozy are simplified as well, and the administration interface makes it easy to keep the platform and application up-to-date.

# Cozy in Five Keywords

- **Openness** Cozy is released under an open source license and users are encouraged to tweak it and build upon it. Developers can extend Cozy's functionality by writing apps and connectors.
- **Privacy** One of Cozy's main design goals is to give the user the ability to keep their personal data on their own machine instead of third-party commercial services and web apps.
- **Simplicity and ease of use** Cozy is designed with regular non-technical users in mind. Most of Cozy's apps are easy to master and straightforward in use.
- **Adaptability** Most of Cozy's functionality is implemented via apps. So users can adapt the platform to their specific needs by installing only the apps they need.
- **Self-hosted** Cozy is designed to be deployed and hosted on a physical or virtual server. For users who don't want to manage a server, Cozy is working with hosting services to provide a plan that offers a virtual private server running Cozy. This way, users can use Cozy without the hassle of hosting it on their own hardware.

# Cozy Target Audience

Cozy's target audience can be roughly divided into two groups.

- Users looking for a simple, adaptable, and powerful self-hosted platform that makes it possible to perform common tasks like sharing and synchronizing files and photos, managing calendars and contacts, working with email, etc. This also includes privacy-conscious users interested in alternatives to popular third-party services and web apps. Together, these users act as facilitators that introduce Cozy to a wider non-technical audience of friends and family members.
- Developers and hackers interested in using Cozy as a platform for building apps and connectors.

# Cozy and Other Cloud Platforms

For an in-depth look at how Cozy compares to other cloud platforms, please see the [Comparison]() page. But here are a few important points.

- **Cozy and ownCloud** ownCloud is first and foremost a collaboration solution, while Cozy is a personal platform. As such, Cozy focuses on functionality for aggregating, managing, and sharing personal data instead of features like collaborative editing, versioning, user management, and access control.

- **Cozy and Pydio** Pydio is a file hosting and collaboration platform geared towards businesses and workgroups. Cozy offers a dedicated, simple and user-friendly app for storing and sharing files, and it's only part of the platform's overall functionality.

- **Cozy and Google Appps** Cozy is an open platform that provides an alternative to Google apps and services. Cozy's Files app, for example, can replace the Google Drive service, while the Calendar app offers an alternative to Google Calendar. There is no complete feature overlap, though. Google Drive, for example, offers more advanced functionality than the Files app in Cozy, while the Google Docs service has no direct equivalent in Cozy. On the other hand, Cozy offers support for connectors for personal data aggregation and analysis. More importantly, though, Cozy provides a foundation for users' own projects and experiments: from building custom apps to aggregating and analyzing personal data.

# Reviewer's Guide

## Installing Cozy

There are several ways to install and run Cozy.

- Install Cozy on Raspberry Pi 2 Model B. A minimal Raspbian distribution with Cozy installed and configured is available as an image file that can be used to create a bootable SD card. Please see the [Install Cozy on a Raspberry Pi](https://cozy.io/en/host/install/install-on-raspberry.html) page for further info.
- Cozy is available through a dedicated software repository for Debian and Ubuntu. This means that Cozy can be installed on a physical machine or virtual private server running Debian or Ubuntu using the APT package manager. Please see the [Install Cozy on Ubuntu](https://cozy.io/en/host/install/install-on-ubuntu.html) and [Install Cozy on Debian](https://cozy.io/en/host/install/install-on-debian.html) pages for further info.
- You can run Cozy as a virtual machine using VirtualBox. Please see the [Install Cozy on VirtualBox](https://cozy.io/en/host/install/install-on-virtualbox.html) page for further info.
- As a member of the media, you can request a hosted instance of Cozy for testing and reviewing purposes. Please contact us at press@cozycloud.cc if you would like to use this option.

## Getting Started with Cozy

During the first run, you'll be prompted to create a user account. Once you've done that, you're dropped into Cozy's main interface.

Cozy is frequently updated, so before you start using Cozy, you should upgrade your installation. To do this, switch to the **Status** section and press the **Update Stack and Applications** button.

All functionality in Cozy is implemented via apps, and the platform comes with its own store which lets you browse and install apps with ease. The list of apps currently available in the store includes the official Files and Photos apps that turn Cozy into a capable file storage and photo publishing platform. So these are the apps you might want to install right away. To do this, click on the desired app entry in the store, review the required permissions and hit **Install**. (see screenshot-1.png)

The Files app lets you easily upload individual files and entire folders using the appropriate buttons. Alternatively, you can drag and drop files and folders onto the Files page to upload them. To manage files and folders efficiently, you can assign tags to them (see screenshot-2.png). To share files or folder, click on the **Share** icon, copy the generated sharing link and press **OK** (see screenshot-3.png). You can then send the link to other users to give them direct access to the shared file or folder. Instead of sending the link, you can share the file or folder with specific users by adding their email addresses in the Sharing dialog. When doing this, you can define access rights for each added email address. When you press **OK**, the system automatically sends email notifications to specified recipients.

Photos app is designed for publishing and sharing photos. All photos in the app are organized into albums (see screenshot-4.png). To create a new album, press the **Create a New Album** button. Give the album a name and a short description, then upload photos using the appropriate button or by dragging and dropping them onto the page. If you already have photos in the Files app, you don't need to upload them again. Press the dedicated button, and pick the photos from the Files app. The Photos app also features sharing capabilities, and the viewing interface in the app makes it possible to view photos, mark them as favorites, rotate and delete them. There is also a slideshow mode that displays photos in the currently selected album as a slideshow (see screenshot-5.png).

The Calendar provides all essential tools for managing tasks and events. The app supports multiple calendars, and you can assign different color labels to them. You can switch between different views, including, Week, Month, and List. To add a calendar entry, click on the desired date in the calendar. For each entry, you can specify start and end (or mark the entry as an all-day event), add location, and assign guests (See screenshot-6.png). There is also an option to set up a reminder to notify you about the upcoming event. It's possible to mark the entry as repeating and specify its recurrence.

The Emails app can handle multiple email accounts spread across several email service providers, and it features a lightweight and functional webmail interface (see screenshot-7.png). As long as your email account supports the IMAP and SMTP protocols, it will work fine with the app. During the first run, Emails prompts you to configure at least one email profile. If you happen to use popular email services like Gmail or Yahoo! Mail, the app automatically fills out the required IMAP and SMTP settings. All email threads in the app are grouped into conversations, making it easier to keep track of correspondence with a specific recipient. You can star important emails and filter messages by several criteria. Using the date filtering functionality, it's possible to quickly display messages for a certain period of time or even a specific date. Of course, there is also a search feature that can help you to find emails matching various criteria.

Cozy app store contains several useful third-party apps. The Ghost app, for example, is suitable for maintaining a simple personal blog, while the Cozic player enables music streaming needs.

## Cozy App for Android

Cozy app for Android makes it possible to synchronize files, calendars, and contacts between an Android device and the Cozy platform (see screenshot-8.png). The app also provides the ability to automatically back up photos on the Android device to Cozy. You can install the app via the [Google Play Store](https://play.google.com/store/apps/details?id=io.cozy.files_client). Alternatively, you can download the latest [APK package](https://cozy.io/en/mobile/files.html) and install it manually. To enable calendar and contacts synchronization in Cozy, you need to install the Sync app from the Cozy app store. Please check the [Contacts Syncronization](https://cozy.io/en/mobile/contacts.html) and [Calendar Synchronization](https://cozy.io/en/mobile/calendar.html) pages for further info.

# Useful Links and Contact Info

Media contact:
For any media and press-related inquires, please contact Cozy at press@cozycloud.cc

Cozy website: https://cozy.io/
Cozy forums: https://forum.cozy.io/
GitHub: https://github.com/cozy
IRC: #cozycloud at Freenode.net
