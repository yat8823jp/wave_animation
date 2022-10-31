# Lottie animation

- After Effects
- [Bodymovin](https://exchange.adobe.com/apps/cc/12557) After Effects extension
- [Lottie](https://lottiefiles.com/)
- [Lottie-web](https://github.com/airbnb/lottie-web) animation-player

## Usage

1. Make animation from After Effects
2. Install Bodymovin and use it
3. export in json file
4. Lottie makes an account and uploads json file from Bodymovin
5. Make html, JavaScript and css

## Help

### Load lottie.js in your html file [GitHub](https://github.com/airbnb/lottie-web/tree/master/build/player)

### 1. Add code ID element in your HMTL file

```
<div id="example"></div>
```

### 2. Add JavaScript file in your project.

Add to this code.
The example.json from Bodymovin.

```
let animationTivel = lottie.loadAnimation( {
    container: document.getElementById( 'example'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: './js/example.json'
} );
```
