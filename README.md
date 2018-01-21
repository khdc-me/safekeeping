# safekeeping
## What is safekeeping?
A unique approach to storing sensitive data.

Perfect for anyone who is somewhat paranoid when it comes to managing credentials.

What this software does:
* Organize everything in groups
* Build a custom form for each group
* Password protects XML file
* Data is assigned 3 'security levels': 1) public; 2) secure; 3) restricted
* Save public and secure data (encrypted) to XML (locally)
* Save restricted data (encrypted) to XML (usb device)

## Security Levels
safekeeping handles data in 3 ways. First, it is important to state that ALL data is stored in encrypted format. The differences are observed on the front end, and the location where the information is found.

**Public**
The first security level is 'Public.' This is stored (encrypted) locally and is displayed after logging into safekeeping. Let's say you store your home network information in safekeeping. Your firewall's node name and details about the manufacturer or model number would be displayed when you log in so that you can readily identified the records.

**Secure**
Fields w/ this security level are also stored (encrypted) locally, alongside public data. The difference is, however, when the data is displayed. By default, the content is hidden and only visible after clicking a button. This button toggles the field from hidden to exposed. Using the same home network example used above, this would be passwords to your printer or wireless AP.

**Restricted**
The last security level is 'Restricted.' This information is stored on an external device (ie: encrypted USB thumb drive). Again, using the home network example, this would be passwords for your firewall, AD, DNS, or whatever appliances' information you'd rather keep hidden and detached until needed in the future.

Ideally, in the case of safekeeping your home network information, the encrypted USB device where you've chosen to save your restricted information would never leave your home. It would also be stored in a fireproof safe where you store other valuables. With the exception of someone breaking into your home or someone having access to your computer (physically or remotely), there is essentially no way for anyone to get your restricted (most private) information.

## How to Install
Nothing to install yet.

Version .0.0.0.0.0.0.0.0.0.01 still being built.
