# 🧬 3D Protein Explorer

A single-file, zero-dependency (browser-only) web application for fetching, viewing, and interacting with 3D protein structures and their metadata from the RCSB PDB.

Enter a PDB ID, and the app fetches the protein's abstract, sequence, and domain information, then renders an interactive 3D model.

![Screenshot of the 3D Protein Explorer showing the 6M0J (COVID-19 Spike Protein) structure and its metadata](https://i.imgur.com/WrU9Zh0.jpeg)

## ✨ Features

* **Search by PDB ID:** Enter any PDB ID (e.g., `1TIM`, `6M0J`, `2HHB`) to fetch data.
* **Detailed Information:** View the protein's common name, its official title, and its functional abstract.
* **Sequence Viewer:** Displays the protein's complete one-letter amino acid sequence.
* **Domain Annotations:** Lists key functional and structural domains from Pfam, CATH, and SCOP.
* **Interactive 3D Viewer:** Powered by **NGL.js**, allowing you to rotate, pan, and zoom the 3D structure.
* **Multiple Representations:** Instantly toggle the 3D model view between:
    * Cartoon
    * Surface
    * Ball & Stick
    * Spacefill
* **Spin Animation:** A simple toggle button to start and stop an automatic spin animation for easy viewing.
* **Responsive Design:** Usable on both desktop and mobile browsers.

## 🚀 How to Use

This is a single-file application. No build step or server is required.

1.  **Save the Code:** Save the complete code as `protein_explorer.html`.
2.  **Open in Browser:** Open the `protein_explorer.html` file in any modern web browser (like Chrome, Firefox, or Edge).
3.  **Search:** Type a PDB ID into the search bar (e.g., `1TIM`) and press "Search" or hit Enter.

## Demo Link
https://swapnilgopale.github.io/3D-Protein-Explorer/

## 🛠️ Technologies Used

* **HTML5**
* **Tailwind CSS (via CDN):** For all styling and layout.
* **JavaScript (ES6+):** For all application logic, API calls, and DOM manipulation.
* **NGL.js (via CDN):** For the interactive 3D WebGL viewer.
* **RCSB PDB API (v1):** Used to fetch all protein metadata, sequence, and domain information.

## Data Source

This project relies on the free and open APIs provided by the **RCSB Protein Data Bank (PDB)**. All protein data and structure files are sourced from them.

