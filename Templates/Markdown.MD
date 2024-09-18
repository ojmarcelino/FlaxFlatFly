<h1 align="center"><project-name></h1>

<p align="center"><project-description></p>

## Links

- [Repo](https://github.com/ojmarcelino/<project-name> "<project-name> Repo")

- [Live](<Homepage url> "Live View")

- [Bugs](https://github.com/ojmarcelino/<project-name>/issues "Issues Page")

- [API](<API Link> "API")

## Screenshots

![Home Page](/screenshots/1.png "Home Page")

![Alternate Text](/screenshots/2.png)

![Alternate Text](/screenshots/3.png)

## Available Commands

In the project directory, you can run:

### `npm start" : "react-scripts start"`

The app is built using `create-react-app` so this command Runs the app in Development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser. You also need to run the server file as well to completely run the app. The page will reload if you make edits.
You will also see any lint errors in the console.

### `"npm run build": "react-scripts build"`

Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance. The build is minified and the filenames include the hashes. Your app will be ready to deploy!

### `"npm run test": "react-scripts test"`

Launches the test runner in the interactive watch mode.

### `"npm run dev": "concurrently "nodemon server" "npm run start"`

For running the server and app together I am using concurrently this helps a lot in the MERN application as it runs both the server (client and server) concurrently. So you can work on them both together.

### `"serve": "node server"`

For running the server file on you can use this command.

### `npm run serve`

  ```Python
  import urllib.request
  from bs4 import BeautifulSoup

  url = 'https://news.google.com'
  origin = urllib.request.urlopen(url).read()
  google_news_soup = BeautifulSoup(origin, "html.parser")

  titles = google_news_soup.select(".title")

  headlines = [title.text for title in titles]

  def search_news(headlines, keys):
    return [headline for headline in headlines if keys.lower() in headline.lower()]

  print(search_news(headlines, "palavra-chave"))
  ```

## Built With

- JavaScript
- Node
- NPM
- Webpack
- HTML
- CSS

## Future Updates

- [ ] Reliable Storage

## Author

### **Juliano Marcelino**

- [Profile](https://github.com/ojmarcelino)
- [Website](https://jmarcelino.com.br)

## 🤝 Support

Contributions, issues, and feature requests are welcome!

Give a ⭐️ if you like this project!
