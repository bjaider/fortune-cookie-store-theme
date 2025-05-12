
# Fortune Cookie Store Theme

**Fortune Cookie Store Theme** is a custom storefront theme built for the **VTEX IO** platform. It displays fortune cookie-style messages to users, designed to work seamlessly with the [Fortune Cookie Admin App](https://github.com/bjaider/fortune-cookie-admin-app).

## 🎯 Purpose

This theme serves as the frontend implementation for the Fortune Cookie functionality, fetching and displaying messages configured by store admins.

## 🚀 Features

- Dynamic rendering of fortune messages.
- Integration with the backend logic from the Admin App.
- Custom design assets and styling.
- Compatible with VTEX IO theme customization practices.

## 📁 Project Structure

- `.github/`: Repository metadata and CI workflows.
- `assets/`: Static assets like images and fonts.
- `docs/`: Documentation files.
- `store/`: Theme configuration and blocks.
- `styles/`: styles for store layout.

## 📦 Setup Instructions

> 🛠️ **Prerequisite:** Make sure you have the [VTEX IO CLI installed](https://developers.vtex.com/docs/guides/vtex-io-documentation-vtex-io-cli-install) on your machine.

1. Clone the repository:

   ```bash
   git clone https://github.com/bjaider/fortune-cookie-store-theme.git
   cd fortune-cookie-admin-app
   ```

2. Log in to your VTEX account:

   ```bash
   vtex login {your-account}
   ```

3. Use the workspace:

   ```bash
   vtex use {your-workspace}
   ```

4. Link the app:

   ```bash
   vtex link
   ```

5. Open the app in the VTEX Admin:

   ```
   https://{your-workspace}--{your-account}.myvtex.com/admin/app/fortune-cookie
   ```

## ⚙️ Configuration

This theme depends on the [Fortune Cookie Admin App](https://github.com/bjaider/fortune-cookie-admin-app). Make sure it's installed and that you've set the **AppKey** and **AppToken**.

You can configure them at:

```
https://{your-workspace}--{your-account}.myvtex.com/admin/apps/valtech.fortune-cookie-app@1.0.2/setup
```

You should see a screen like the following one (see image below):

![image](https://github.com/user-attachments/assets/fe206bbe-125e-4241-a0a8-d6bcf643f597)

## 📬 Contact

- Developer: Jaider Bermudez  
- GitHub: [@bjaider](https://github.com/bjaider)




