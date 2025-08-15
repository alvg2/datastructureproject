# Data Structure and Algorithm Visualization Project

Project report: <a href="https://github.com/alvg2/datastructureproject/blob/main/pdfs/download_pdf.html" target="_blank">View My PDF</a>

<a href="./pdfs/Project_Report.pdf" download="My_Document.pdf">Download My PDF</a>


- to open enter the following twice: v23GhQkp#cBf!@P!

Project printout:[Personal Website Link](
- to open enter the following twice: 

For contact information visit my personal website: [Personal Website Link](https://alvg2.github.io/personal-website/)



<body>

    <h1>PDF Download Example</h1>

    <button onclick="downloadPdf()">Download Project Report (Button)</button>

    <br><br>

    <a href="#" onclick="downloadPdf(event)" download="My_Project_Report.pdf">Download Project Report (Link)</a>

    <script>
        function downloadPdf(event) {
            // Prevent the default link behavior if it's an anchor tag
            if (event) {
                event.preventDefault();
            }

            // Make sure this path is correct relative to THIS HTML file
            // If download_pdf.html is in the root, and pdfs/ is a folder in the root:
            const pdfUrl = './pdfs/Project_Report.pdf'; 

            // If your PDF is directly in the same folder as this HTML file:
            // const pdfUrl = 'Project_Report.pdf';

            const suggestedFileName = 'My_Project_Report.pdf'; // Desired filename for download

            // Create a temporary anchor element
            const link = document.createElement('a');
            link.href = pdfUrl;
            link.download = suggestedFileName; // Set the download attribute

            // Append to the body (not strictly necessary for click() but good practice)
            document.body.appendChild(link);

            // Programmatically click the link to trigger the download
            link.click();

            // Clean up: remove the temporary link
            document.body.removeChild(link);
        }
    </script>

</body>
