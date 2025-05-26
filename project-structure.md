# Community Resource Hub - Project Structure

```
community-resource-hub/
├── src/
│   ├── assets/
│   │   ├── images/
│   │   │   └── placeholder.jpg
│   │   ├── icons/
│   │   └── fonts/
│   ├── styles/
│   │   ├── components/
│   │   │   ├── _cards.css
│   │   │   ├── _navbar.css
│   │   │   ├── _sidebar.css
│   │   │   ├── _modals.css
│   │   │   └── _forms.css
│   │   ├── layouts/
│   │   │   ├── _grid.css
│   │   │   └── _containers.css
│   │   ├── utils/
│   │   │   ├── _variables.css
│   │   │   ├── _animations.css
│   │   │   └── _helpers.css
│   │   └── main.css
│   ├── js/
│   │   ├── components/
│   │   │   ├── resourceCard.js
│   │   │   ├── searchFilter.js
│   │   │   └── modalHandler.js
│   │   ├── utils/
│   │   │   ├── api.js
│   │   │   └── helpers.js
│   │   └── main.js
│   ├── components/
│   │   ├── navbar.html
│   │   ├── sidebar.html
│   │   ├── resourceCard.html
│   │   └── footer.html
│   └── pages/
│       ├── index.html
│       ├── courses.html
│       ├── hackathons.html
│       ├── internships.html
│       └── resources.html
├── public/
│   ├── favicon.ico
│   └── robots.txt
├── dist/
│   ├── css/
│   ├── js/
│   └── assets/
└── package.json
```

## Directory Structure Explanation

### `/src`
Main source code directory containing all the development files.

#### `/src/assets`
- `images/`: Project images and graphics
- `icons/`: Icon files
- `fonts/`: Custom font files

#### `/src/styles`
- `components/`: Component-specific styles
- `layouts/`: Layout and grid system styles
- `utils/`: Utility styles, variables, and mixins
- `main.css`: Main stylesheet importing all other styles

#### `/src/js`
- `components/`: JavaScript modules for specific components
- `utils/`: Utility functions and helpers
- `main.js`: Main JavaScript file

#### `/src/components`
Reusable HTML components that can be included in pages

#### `/src/pages`
Individual HTML pages for different sections of the site

### `/public`
Static files that don't require processing

### `/dist`
Compiled and processed files ready for production