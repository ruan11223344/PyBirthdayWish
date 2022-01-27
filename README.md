<p align="center">
<img src="image/PyBirthdayWish.gif" align="center" alt="PyBirthdayWish GIF" />
<h2 align="center">用python祝福你爱的人吧</h2>
</p>
<p align="center">

## 🕯️ 建议打包为可执行文件发送给对方
* 安装依赖
```bash
    pip install -r requirements.txt
```

* 用Python3 运行 ``PyBirthdayWish.py``
    ```bash
    python3 PyBirthdayWish.py
    ```

* 如果一切正常，您可以使用下面的命令使用pyinstaller创建一个可执行文件
    * windows
        ```bash
        pyinstaller --noconfirm --onefile --console --icon "icon.ico" --add-data "arts;arts/"  --add-data "config.py;." --add-data "HappyBirthday.mp3;." --add-data "PyBirthdayWish.py;."  "PyBirthdayWish.py"
        ```
    * 其他系统
        ```bash
        pyinstaller --noconfirm --onefile --console --icon "icon.ico" --add-data "arts:arts/"  --add-data "config.py:." --add-data "HappyBirthday.mp3:." --add-data "PyBirthdayWish.py:."  "PyBirthdayWish.py"
        ```
