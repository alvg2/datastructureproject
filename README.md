# Data Structure and Algorithm Visualization Project

Project report:  <a href="#" onclick="downloadPdf(event)" download="My_Project_Report.pdf">Download Project Report PDF (Link)</a>
<body>

    <script>
        function downloadPdf(event) {
            // Prevent the default link behavior for the pdf (force downloading, prevent opening)
            if (event) {
                event.preventDefault();
            }

            // File path
            const pdfUrl = './pdfs/Project_Report.pdf'; 

            // Desired filename for download
            const suggestedFileName = 'My_Project_Report.pdf'; 

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
- to open enter the following twice: v23GhQkp#cBf!@P!

Project printout:  <a href="#" onclick="downloadPdf(event)" download="Project_Printout.pdf">Download Project Printout PDF (Link)</a>
<body>

    <script>
        function downloadPdf(event) {
            // Prevent the default link behavior for the pdf (force downloading, prevent opening)
            if (event) {
                event.preventDefault();
            }

            // File path
            const pdfUrl = './pdfs/Project_Printout.pdf'; 

            // Desired filename for download
            const suggestedFileName = 'My_Project_Printout.pdf'; 

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
- to open enter the following twice: qcLFUS6p&t9d$tEV

For contact information visit my personal website: [Personal Website Link](https://alvg2.github.io/personal-website/)




