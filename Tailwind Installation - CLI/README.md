# Tailwind CSS Installation Using CLI ✅

## 🌟 Installation

1. Install NodeJS in your system.

2. Install tailwind CSS as dev-dependancies and Initialize it using following commands.

```bash
npm install -D tailwindcss
```

```bash
npx tailwindcss init
```

3. Install Tailwind CSS Intellisense Extension.

4. Update tailwind.config.js file to include this line.

```
content: ["*.html"]
```

5. Create src/input.css to include.

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

6. Include the src/output.css file to your html.

7. Run the following Command.

```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

## 🛠 Customizing watch command for Running File

1. Now go to **package.json** file in that file go to scripts in scripts add "start" name script.

2. Copy Below Command and paste it scripts in **package.json**.

```
"start": "npx tailwindcss -i ./src/input.css -o ./src/output.css --watch"
```

3. For starting your tailwind CSS project run following command.

```bash
npm run start
```

### READY TO GO NOW... 😎 !!!

## 📖 Additional Resources

- [Official Tailwind CSS Documentation](https://tailwindcss.com/docs/installation)

---

:heart: Follow Me For More Projects [GitHub](https://github.com/ChinmayKaitade) | [LinkedIn](https://www.linkedin.com/in/chinmay-sharad-kaitade) | [Email](chinmaykaitade123@gmail.com)
