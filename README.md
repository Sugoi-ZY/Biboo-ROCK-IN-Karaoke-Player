# ⚠️v2 is coming soon. / 第二版即將到來。

## Running the File Locally
Due to YouTube Player API restrictions (CORS / `file://` protocol limitations), opening the HTML file directly will not work.\
It must be served through a web server.

If you have Python installed:
1. Open Command Prompt (CMD) in the directory where the HTML file is located.
2. Run `py -m http.server` (or `python -m http.server`) to launch a local web server.
3. Open `http://localhost:8000` in your browser.

## 開啟檔案的注意事項
由於 YouTube 播放器的限制，HTML 檔無法直接開啟使用，需將其放置於 Web Server 下，才能正常使用。\
電腦有裝 Python 的，在 HTML 目錄下，開啟 CMD，再透過 `py -m http.server` 開啟 Web Server，即可正常使用。
