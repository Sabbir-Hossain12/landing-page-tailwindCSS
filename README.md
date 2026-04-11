Install Tailwind CSS
- Install tailwindcss and @tailwindcss/cli via npm.
```terminaloutput
npm install tailwindcss @tailwindcss/cli
```

Import Tailwind in your CSS
- Add the @import "tailwindcss"; import to your main CSS file.

```terminaloutput
@import "tailwindcss";
```

Start the Tailwind CLI build process
- Run the CLI tool to scan your source files for classes and build your CSS.
```terminaloutput
npx @tailwindcss/cli -i ./asset/css/input.css -o ./asset/css/output.css --watch
```

Start using Tailwind in your HTML
- Add your compiled CSS file to the <head> and start using Tailwind’s utility classes to style your content.
```html
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="asset/css/output.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>
```


