# 07
# Neurosynth Frontend

This web application provides a user-friendly interface for exploring Neurosynth data using AJAX and Tailwind CSS. The UI is split into two main panels: search options (left) and results (right).

## Features

### Left Panel: Search Options

1. **Search all available terms**
   - Click "Fetch All Terms" to display all available terms in a paginated table.
   - Filter terms by their starting alphabet (A-Z) using the alphabet selector above the results-per-page selector.
   - Select how many results to show per page.

2. **Search associated terms**
   - Enter a term in the input box and click "Fetch Term Details" to display related terms (with co-occurrence count) in a paginated table.
   - Real-time suggestions appear as you type.
   - Select how many results to show per page.

3. **Logical study search**
   - Enter up to 5 terms and select logical operators (AND, OR, NOT) to build a multi-term query.
   - Click "Search Studies" to display matching studies in a paginated table.
   - Select how many results to show per page.

### Right Panel: Search Results

- Displays results for the selected search function in a table format.
- Shows total number of results and supports pagination.
- Results-per-page selector and alphabet filter (for terms) are available above the table.

## Usage

1. Open `index.html` in your browser.
2. Use the left panel to select a search function and view results in the right panel.
3. Use the alphabet filter and results-per-page selector for term searches.
4. Use logical operators for advanced study searches.

## Technologies
- HTML, JavaScript (AJAX/fetch API)
- Tailwind CSS for styling

## File Structure
- `index.html`: Main application UI and logic
- `README.md`: Project documentation

## License
MIT
