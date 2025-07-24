# Azure Static Website Project

This project demonstrates how to deploy a simple static website using Azure Storage.

## Files Included
- `index.html`: The homepage of the website
- `styles.css`: Basic styling for the homepage

## Steps to Deploy on Azure

1. **Create a Storage Account**
   - Go to the Azure Portal
   - Create a new Storage Account (Standard, General-purpose v2)

2. **Enable Static Website Hosting**
   - In the Storage Account, go to `Static website` under `Settings`
   - Enable static website hosting
   - Set `index.html` as the index document

3. **Upload Files**
   - Go to `Containers` > `$web`
   - Upload `index.html` and `styles.css` to this container

4. **Access Your Website**
   - Use the primary endpoint URL provided in the Static Website settings to view your site

## Author
Chike Egbuniwe
