# AI Coding Agent Instructions for JQUERY-MASTER2025

## Project Overview
This project is a collection of HTML, CSS, and JavaScript files that demonstrate various functionalities using jQuery and Bootstrap. The project includes examples of CRUD operations, dynamic content generation, and integration with external APIs. The structure is organized into individual HTML files, each showcasing a specific feature or functionality.

### Key Components
- **HTML Files**: Each file (e.g., `web29homepracticafinaldoctores.html`) represents a standalone example or feature.
- **CSS**: Custom styles are located in the `css/` directory. Bootstrap is used extensively for styling.
- **JavaScript**: jQuery is the primary library for DOM manipulation and AJAX requests. Additional scripts are in the `js/` directory.
- **Data Files**: XML and JSON files in the `documents/` directory are used for data-driven examples.
- **Images**: Static assets are stored in the `images/` directory.

## Developer Workflows

### Running the Project
1. Open any HTML file in a browser to view the corresponding example.
2. Ensure that the `css/` and `js/` directories are correctly linked in the HTML files.

### Debugging
- Use browser developer tools to inspect elements and debug JavaScript.
- Check the console for AJAX request logs and errors.

### Adding New Features
1. Create a new HTML file in the root directory.
2. Link the necessary CSS and JavaScript files.
3. Follow the existing patterns for structure and functionality.

## Project-Specific Conventions
- **CSS**: Use Bootstrap classes for layout and styling. Add custom styles in `custom.css` if needed.
- **JavaScript**: Use jQuery for DOM manipulation and AJAX requests. Follow the pattern of defining functions and calling them on `$(document).ready()`.
- **HTML**: Maintain semantic structure. Use Bootstrap components for consistency.

## Integration Points
- **External APIs**: Some examples, like `web29homepracticafinaldoctores.html`, fetch data from external APIs. Ensure the API URLs are correct and accessible.
- **Data Files**: XML and JSON files are used for local data examples. Update these files as needed for new features.

## Examples of Patterns
### AJAX Request
```javascript
$.ajax({
    url: "https://example.com/api",
    type: "GET",
    dataType: "json",
    success: function(data) {
        console.log(data);
    }
});
```

### Bootstrap Table
```html
<table class="table table-bordered">
    <thead>
        <tr>
            <th>Column 1</th>
            <th>Column 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
        </tr>
    </tbody>
</table>
```

## Key Files and Directories
- **HTML Files**: Root directory
- **CSS**: `css/`
- **JavaScript**: `js/`
- **Data**: `documents/`
- **Images**: `images/`

## Notes
- Ensure all dependencies (e.g., jQuery, Bootstrap) are correctly linked.
- Follow the existing structure and conventions to maintain consistency.

---

Feel free to update this document as the project evolves.