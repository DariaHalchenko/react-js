# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

## Episode 10

<img width="810" height="214" alt="{94F2DD13-0A52-42AC-8D28-84005DAFB74D}" src="https://github.com/user-attachments/assets/83f2f16e-6a20-4976-b48b-be724dab84a3" />

<img width="461" height="135" alt="{0B29D937-57DE-477A-A764-0BD5EF3C3A4D}" src="https://github.com/user-attachments/assets/6f928b51-4d55-4c64-bb88-6369429c35ee" />

<img width="544" height="138" alt="{F350059E-F31F-4BA2-99D9-B2DCA3D824B9}" src="https://github.com/user-attachments/assets/f63051cc-22c0-4aec-93ea-21b050dbdc1c" />

- Selles näites kasutatakse React Router DOMi raamatukogu rakenduse lehtede vahel navigeerimiseks ja @tanstack/react-query API päringute ja andmete puhverdamiseks.
- BrowserRouter (Router) komponendi abil luuakse marsruutimissüsteem ning Route ja Routes komponendid määravad lehtede Home, Profile ja Contact asukohad.
- Navbar komponent kuvatakse igal lehel ja sisaldab linke nende vahel liikumiseks.
- Komponent QueryClientProvider ümbritseb kogu rakendust ja pakub React Query klienti (QueryClient) päringute haldamiseks, nende puhverdamiseks ja uuendamiseks.
- Kui kasutaja sisestab olematu aadressi, käivitub marsruut *, mis kuvab sõnumi „PAGE NOT FOUND”.
