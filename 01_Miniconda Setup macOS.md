# Installing Miniconda3 and Jupyter Notebook on Mac

This guide is for Mac users who wish to install Miniconda3 and Jupyter Notebook. If you already have Anaconda or Miniconda installed, you can skip this manual.

## What is Miniconda?

Miniconda is a free minimal installer for conda. It is a smaller alternative to Anaconda, aiming to provide conda (a package manager and environment manager) and a select number of essential packages. Unlike Anaconda, which comes pre-loaded with a wide range of data science packages, Miniconda allows you to create environments tailored to your specific needs, ensuring a lightweight and efficient setup.

### Step 1: Download Miniconda3

First, determine your Mac's architecture (Apple Silicon or Intel-based) to download the correct version of Miniconda3.

1.  Visit the [Miniconda download page](https://docs.anaconda.com/free/miniconda/index.html).
2.  Choose the appropriate version based on your Mac's CPU architecture:
    -   For Apple Silicon (M1, M2, etc.): Download **Miniconda3 macOS Apple M1 64-bit pkg**.
    -   For Intel-based Macs: Download **Miniconda3 macOS Intel x86 64-bit pkg**.

### Step 2: Install Miniconda3

1.  Locate the downloaded `.pkg` file in your Downloads folder or wherever you chose to save it.
2.  Double-click the package to start the installation process.
3.  Follow the on-screen instructions to complete the installation.

### Step 3: Install Jupyter Notebook

After installing Miniconda3, you'll need to open the Terminal app to install Jupyter Notebook.

1.  Open **Terminal** (you can find it using Spotlight search with `Cmd + Space` and typing "Terminal").

2.  In the Terminal, type the following command and press Enter:

    ``` sh
    pip install jupyter
    ```

3.  Wait for the installation to complete. This might take a few minutes depending on your internet connection.

### Step 4: Launch Jupyter Notebook

With Jupyter Notebook installed, you can now launch it directly from the Terminal.

1.  In the Terminal, type the following command and press Enter:

    ``` sh
    jupyter notebook
    ```

2.  This command will start the Jupyter Notebook server and open it in your default web browser. If it doesn't open automatically, you can manually navigate to the provided URL (typically `http://localhost:8888/tree`).

### Final Step: Enjoy Jupyter Notebook

You're all set! You can now begin creating new notebooks, writing code, analyzing data, and much more with Jupyter Notebook on your Mac.

Remember, this guide is specifically for users who don't have Anaconda or Miniconda installed. If you already use these tools, you can directly install Jupyter Notebook without needing to reinstall Miniconda.
