
# Redmine Notification App

The Redmine Notification App is a desktop application that provides instant notifications when a new ticket is assigned to you on your Redmine account. This app helps you stay updated with your Redmine tasks without the need to constantly check your account.

## Features

- **Real-Time Notifications**: Get immediate notifications when a new issue is assigned to you in Redmine.
- **Customizable Settings**: Set up your API key and Redmine URL for seamless integration.
- **Desktop Notifications**: Get alerts even when the app is minimized.
- **API Key and Redmine URL Management**: Easily reset and update your settings anytime.
- **Persistent Settings**: The app remembers your settings and restores them even after restarting.

## Requirements

- **Node.js**: Make sure Node.js is installed on your machine.
- **Electron**: The app is built using Electron, which allows you to run the app as a desktop application.

## Installation

1. Clone the repository:

``` bash
   git clone https://github.com/yourusername/redmine-notification-app.git
```

2. Navigate into the project directory:

```bash
   cd redmine-notification-app
  ```
3. Extract the zip file inside of the folder 


4. Install the required dependencies:

```bash
   npm install
```

5. Run the application:

```bash
   npm start
 ```

## Steps to Set Up the Redmine Notification App

1. **Log in to Redmine**:  
   Open the Redmine application and log in using your credentials.

  
3. **Retrieve API Key**:  
   Navigate to the 'My Account' section (found on the right side of the interface).  
   Under 'API Access Key', click on 'Show' to reveal your API key.  
   Copy the API key for use in the next step.
   
    ![REDMINE NOTIFICATION SETUP](https://github.com/user-attachments/assets/21e31502-5af7-4567-8b6d-1c23ea15b7c9)

5. **Set Up the Notification App**:  
   Open the Redmine Notification App.  
   Paste the copied API key into the designated input field.  
   Enter your Redmine URL into the application.  
   Click 'Save' to store your settings.

6. **Run the Application**:  
   Minimize the application instead of closing it. Closing the app will stop the notifications from working.

   ![TICKET NOTIFICATION](https://github.com/user-attachments/assets/1ce7f5ca-9d17-44e4-9a28-dfa291ecc76a)


7. **Important Note**:  
   Make sure your firewall is turned off; otherwise, the notifications might not function properly.

## Development

### Build for Production

To build the app for production:

```bash 
npm run build
```

This will generate the necessary files for deployment.

### Packaging for Desktop (Windows)

To package the app for use as a desktop application:


```bash 
npm run package
```

This will bundle the app into a format that can be distributed and installed on both 32-bit and 64-bit systems.

## Contributing

If you'd like to contribute to the project, please fork the repository and submit a pull request. Any contributions are welcome.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

### Author

**Amrit Lamsal**  
For queries, you can reach me via email at [amritlamsal400@gmail.com](mailto:amritlamsal400@gmail.com).
