# pm2-stand-alone

pm2-stand-alone generates an independent executable file of the pm2 process manager that can be used without affecting the existing Node.js environment and without the need for Node.js and npm installation. This project is a tool for developers and system administrators who want to use pm2 in various Node.js versions and environments.

## Why Use pm2-stand-alone?

- **Node.js and npm Version Management**: When you want to use pm2 functionality without affecting the Node.js version your existing program relies on, pm2-stand-alone is the ideal choice.

- **No npm and Package Management Required**: You don't need to install Node.js and npm separately. You can use pm2 even in small-scale environments or situations with restricted Node.js environment settings.

- **Simple Deployment**: pm2-stand-alone is provided in the form of an executable file, making deployment and execution simple and convenient.

## Features (Same as pm2)

- Application start, stop, restart, and monitoring.
- Log file management and output support.
- Environment variable setup and management.
- Running applications in the background.

## Creating pm2-stand-alone

Getting started with pm2-stand-alone is straightforward.

### 1. Install Dependencies

In the project's root directory, install the necessary packages using the following command:

```bash
npm install
```

### 2. Generate Executable Files
To generate the executable files, run the following command:

```bash
npm run pkg
```

## Using pm2-stand-alone
You are now ready to use pm2-stand-alone! Run the generated executable file and manage your applications. The usage is the same as with pm2.

Example:
```bash
./pm2-stand-alone start <program to manage> --interpreter none --name "<program alias>"
```

## License
This project is distributed under the MIT License. For more details, refer to the [LICENSE](LICENSE) file.
