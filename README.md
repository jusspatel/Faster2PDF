# Faster2PDF
<p align = "center">
<img src = "https://github.com/jusspatel/Faster2PDF/blob/master/untitled.png">
</p>
Faster2PDF is a lightweight Tkinter Programme for converting images to PDF really fast !


## Installation
For v2.0 and 1.0 : 
- Go to releases section of respective version
- Download the repository as zip and extract its contents to the **same folder**.
- Open the folder in which the contents are stored and double click on the `Faster2PDF.exe` file to run it .
- A windows defender message might popup . If it does , click on **More Info** and then click **Run Anyway**
- Wait for 2-10 Seconds
- Voila ! The application should now be running .
For v2.1 and above :
- Follow the same steps , except download the file name Faster2PDF-zip in the releases section of respective version


## How to use it ?
- Once the application opens , you will see a button called `Open Images Files` at the bottom left . Click on it to select the images you want to convert to PDF (Do this as many times as you want.)
- Once that is done , you can also delete the image by just clicking on the image you want on the list and pressing the `Remove Image from list` Button .
- You also have the option of image quality by aadjusting the spinbox given just below the image list . Lowest being 1 and Highest being 95
- Once you have done that , just click on `Convert Images to PDF` Button.
- Now just open the downloads folder on your PC , and you wil see the generated PDF in a matter of few seconds

## Possible Future Updates
- Smaller PDFs upon conversion
- Image reordering option
- PDF to Images

## Made With
- Python , Tkinter , PyInstaller and Pillow 

## Runs on:
- Only Windows for now ;-; .Thinking of making it for other plattforms too in the future

# Releases :

## v1.0
Initial version

## v2.0
- Minor UI Changes
- Added Image Reordering by Just dragging the seleceted image wherever you want in the list
- Added Image Preview by clicking on the File Path
- Added Inbuilt PDF Compression : 
  - If you set Image Quality to 95 (Highest Quality) , 42 MB worth of images get converted into a 45 MB PDF
  - If you set Image Quality to 50 (Medium Quality)(Recommended) , 42 MB worth of images get converted into a 9 MB PDF
  - If you set Image Quality to 25 (Medium Low Quality) , 42 MB worth of images get converted into a 5 MB PDF
- Faster Conversion speeds
