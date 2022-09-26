# Requirements
 * **Python 3.7.x-3.9.x**
 * High speed Internet Connection
 * Good proxy list (http, https, socks4, socks5)
 * Google Chrome installed on your OS (not Chromium)
 * 
# Windows
* ## Binary Release

  For windows you can download binary releases from **[Binary releases](https://github.com/MShawon/YouTube-Viewer/releases)**. Download this file named `YouTube-Viewer_win_x.x.x.zip`, unzip it and run the `youtube_viewer.exe`. Or you can install it from source. To do so keep reading. 
  
* ## Installation

  First, make sure you have installed git and Python version between 3.7.x to 3.9.x
  
  Open command prompt and type
  ```
  git clone https://github.com/MShawon/YouTube-Viewer.git --depth 10
  ```
  ```
  cd YouTube-Viewer
  ```
  ```
  python -m pip install --upgrade pip wheel
  ```
  ```
  pip install "setuptools<59"
  ```
  ```
  pip install -r requirements.txt
  ```

* ## Important
   * If you've got a large free proxies collection, you should run this command to filter Good proxies. Then use **GoodProxy.txt** for proxy in **youtube_viewer.py**
      ```
      python proxy_check.py
      ```

   * After closing program, if chromedrivers are still running. You may want to double click **killdrive.bat** to close all chrome instances.

   * *urls.txt* or *search.txt* can't be empty. Otherwise you will see errors. Use both for better results.

* ## Usage
   * Open command prompt in YouTube-Viewer folder and run
        ```
        python youtube_viewer.py
        ```
   * Rest is self explanatory.

# Linux / Mac
* ## Installation

  First, make sure you have installed git and Python version between 3.7.x to 3.9.x
  
  Open your favourite terminal and run
   ```
  git clone https://github.com/MShawon/YouTube-Viewer.git --depth 10
  ```
  ```
  cd YouTube-Viewer
  ```
  ```
  python3 -m pip install --upgrade pip wheel
  ```
  ```
  pip3 install "setuptools<59"
  ```
  ```
  pip3 install -r requirements.txt
  ```

* ## Important
   * If you've got a large free proxies collection, you should run this command to filter Good proxies. Then use **GoodProxy.txt** for proxy in **youtube_viewer.py**
        ```
        python3 proxy_check.py
        ```

   * After closing program, if chromedrivers are still running. Open your terminal and run 
      ```bash
      ps aux | awk '/chrome/ { print $2 } ' | xargs kill -9
      ```
   * *urls.txt* or *search.txt* can't be empty. Otherwise you will see errors. Use both for better results.

* ## Usage
   * Open command prompt in YouTube-Viewer folder and run
        ```
        python3 youtube_viewer.py
        ```
   * Rest is self explanatory.
