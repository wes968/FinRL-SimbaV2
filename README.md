## 安裝FinRL 以Windows為例 (資料夾不能有中文)
### 1. 使用python 3.9.2 建立虛擬環境
* pyenv選擇python版本
* venv建立虛擬環境
### 2. 更新pip版本 (非常重要)
```
python -m pip install --upgrade pip
```
### 3. 更新setuptools版本 (非常重要)
```
python -m pip install --upgrade setuptools
```
### 4. Clone FinRL
```
git clone https://github.com/AI4Finance-Foundation/FinRL.git
```
### 5. 進入FinRL目錄
```
cd FinRL
```
### 6. 安裝 FinRL 需要的套件
```
pip install .
```
. 代表當前目錄。這個命令會讓 pip 讀取當前目錄下的 setup.py 或 pyproject.toml 配置文件，根據裡面的設定來構建並安裝該項目到你的 Python 環境中
### 7. 執行simba-v2.ipynb、simba-v2_1.ipynb