# Hasil Running Gui
![image](https://user-images.githubusercontent.com/34876769/120765527-80d73400-c543-11eb-8602-25914630c3ee.png)

## Edit destroyed :(
![image](https://user-images.githubusercontent.com/34876769/120765631-98aeb800-c543-11eb-9e98-c5fd75b9f9d2.png)

## Analisa saya
### 

```python
app = QApplication([])
button = QPushButton('Click') 
# button terdeklarasi
def on_button_clicked():
# apabila button clicked
    alert = QMessageBox()
    # menampilkan message
    alert.setText('You clicked the button!')
    alert.exec_()
button.clicked.connect(on_button_clicked)
button.show()
app.exec_();
```
![image](https://user-images.githubusercontent.com/34876769/120766150-238fb280-c544-11eb-9805-a0ab78745b1f.png)

