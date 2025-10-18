# GitHub User Info Dashboard

A web application that fetches and displays a GitHub user's account creation date. It supports an optional GitHub Personal Access Token for API authentication, provided via a URL query parameter.

## Features

*   **GitHub Username Input**: Easily enter any GitHub username to retrieve their profile information.
*   **Account Creation Date**: Displays the user's account creation date in `YYYY-MM-DD UTC` format.
*   **Optional API Token Support**: Includes functionality to use a GitHub Personal Access Token by appending `?token=<YOUR_TOKEN>` to the URL, useful for higher API rate limits or accessing private data (though `created_at` is public).
*   **Bootstrap UI**: Utilizes Bootstrap for a clean, responsive, and modern user interface.
*   **Loading & Error Handling**: Provides a visual loading spinner during API calls and displays clear error messages for failed requests or invalid usernames.
*   **Modern JavaScript**: Implemented using ES6+ features like `async/await`, `const`/`let`, and template literals.

## How to Use

1.  **Open the Application**: Save the `index.html` file and open it in your web browser.
2.  **Enter GitHub Username**: Type a GitHub username (e.g., `octocat`, `google`) into the 