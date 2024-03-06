# Installing Miniconda3 and Jupyter Notebook on Windows

This manual is designed for Windows users who wish to install Miniconda3 and Jupyter Notebook. If you are already a user of Anaconda or Miniconda, you do not need to follow this guide.

## What is Miniconda?

Miniconda is a free minimal installer for conda. It is a smaller alternative to Anaconda, aiming to provide conda (a package manager and environment manager) and a select number of essential packages. Unlike Anaconda, which comes pre-loaded with a wide range of data science packages, Miniconda allows you to create environments tailored to your specific needs, ensuring a lightweight and efficient setup.

### Step 1: Download Miniconda3

To begin, you will need to download the Miniconda installer for Windows.

1.  Navigate to the [Miniconda download page](https://docs.anaconda.com/free/miniconda/index.html).
2.  Download the **Miniconda3 Windows 64-bit** installer.

### Step 2: Install Miniconda3

Once you have downloaded the installer, you can proceed with the installation:

1.  Locate the downloaded `.exe` file, typically in your Downloads folder.
2.  Double-click the file to start the installation process.
3.  Follow the on-screen instructions to install Miniconda. It is recommended to accept the default installation options **Just Me** is recommended.
4.  When the screen appears **add** **to your PATH**, to ensure a smooth setup.

### Step 3: Install Jupyter Notebook

With Miniconda installed, you'll now install Jupyter Notebook using the Miniconda Command Prompt.

1.  Search for **Miniconda3 Command Prompt** in the Windows search bar and open it.

2.  In the Miniconda Command Prompt, type the following command and press Enter:

    ``` cmd
    pip install jupyter
    ```

3.  Wait for the command to complete the installation. This might take a few minutes, depending on your internet speed.

### Step 4: Launch Jupyter Notebook

After installing Jupyter Notebook, you are ready to launch it:

1.  Still in the Miniconda Command Prompt, type the following command and press Enter:

    ``` cmd
    jupyter notebook
    ```

2.  This command starts the Jupyter Notebook server and should automatically open it in your default web browser. If it does not open automatically, you can manually go to the URL displayed in the command prompt (usually [`http://localhost:8888/tree`](http://localhost:8888/tree)).

### Final Step: Begin Using Jupyter Notebook

You are now set to start using Jupyter Notebook on your Windows machine. Create new notebooks to write and execute code, analyze data, and more.

This guide is meant for those who do not have Anaconda or Miniconda previously installed. If you are already using these platforms, you can install Jupyter Notebook directly without needing to reinstall Miniconda.
