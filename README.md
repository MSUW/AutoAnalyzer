# AutoAnalyzer
A tool for running multiple analysis one by one in HFSS

## Before runnig
Download all the files and put them in a **folder**

Change the resource file path in MainForm.py (line 24) into your **folder/Res** before your first time running

It looks like:

```python
Res = "yourpath\\Res\\"
```

For example:

```python
Res = "C:\\Users\\username\\Desktop\\Auto\\Res\\"
```

**Note: use '/' or double'\\' instead of  '\\' , or HFSS will report an error!**

And also edit the path in Program.py (line 8) 

It looks like:

```python
sys.path.append(r"your path")
```

For example:

```python
sys.path.append(r"C:\Users\username\Desktop\Auto")
```
