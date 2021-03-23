# Download-Google-Images
Code to mass download images from Google Images using JavaScript Console Window and python script.

Steps to perform:
- Query your intended Google search
- Scroll down through images until they become unrelated to your query or until you've passed enough images for your dataset
- Right click and hit "Inspect" and then navigate to "Console" tab
- Enter the lines from console.js into the console window and run them
- Move urls.txt from Downloads folder to this folder
- Run follwing two python commands as follows:
```bash
pip install -r requirements.txt
python download_images.py --urls urls.txt --output images
```

You should now have all your images inside your images folder!

## License
[![MIT License](https://img.shields.io/github/license/ashishkrb7/Image-downloader.svg?style=flat-square&colorB=C62121)](https://github.com/ashishkrb7/Image-downloader/blob/master/LICENSE)
```
Copyright (c) 2021 Ashish Kumar
```

## Author
Ashish Kumar

[![LinkedIn](https://img.shields.io/badge/-Ashish%20Kumar-blue?style=social&logo=Linkedin&logoColor=blue&link=https://www.linkedin.com/in/ashishk766/)](https://www.linkedin.com/in/ashishk766/) 
[![Gmail](https://img.shields.io/badge/-Ashish%20Kumar-c14438?style=social&logo=Gmail&logoColor=red&link=mailto:ashish.krb7@gmail.com)](mailto:ashish.krb7@gmail.com) 

Made with ❤️ in India

## Contributors

<a href="https://github.com/ashishkrb7/Image-downloader/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ashishkrb7/Image-downloader" />
</a>
