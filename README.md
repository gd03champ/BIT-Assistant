
<br />
<div align="center">
  <a href="https://github.com/gd2003gamingchamp/BIT-Assistant-pvt">
    <img src="assets/bit.png" alt="Logo" width="80" height="80">
  </a>

  <h2 align="center">BIT Chatbot</h2>

  <p align="center">
    A chatbot for my college that could answer anything asked inside the scope of college and provide corresponding link!
    <p align="center"><b>Scripts are made private due to college restrictions</b></p>
  
 <br>
   
</div>

![image](assets/giffy.gif)


## Tech Stack
👉 NLU <br>
👉 Machine Learning <br>
👉 Beautifulsoup Webscarping <br>
👉 HTML, CSS & JS

## Built With
* [Rasa Framework](rasa.com)
* [Webchat Framework](https://github.com/botfront/rasa-webchat)
* [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/)
* [Python](python.org)

# Getting Started

## Install Dependencies
1. Create virtual environment
```sh
python3 -m venv /path/to/new/virtual/environment
```
2. Activate virtual environment
```sh
path/to/new/virtual/environment\Scripts\activate.ps1
```
3. Install rasa
```sh
pip install rasa
```
4. Install action dependencies
```sh
pip install -r actions/requirements.txt
```

# Run

1. Clone Repository
```sh
git clone https://github.com/gd2003gamingchamp/BIT-Assisstant-pvt.git
```
2. Initiate rasa inside the repo
```sh
rasa init
```
3. Run rasa action server
```sh
rasa run actions
```
4. Trigger rasa main server
```sh
rasa run -m models --enable-api --cors "*"
```
5. Open `index.html` to see bot in action!

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


