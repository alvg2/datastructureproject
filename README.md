# Data Structure and Algorithm Visualization Project

Project report: <a href="https://github.com/alvg2/datastructureproject/blob/main/Project_Report.pdf" target="_blank">View My PDF</a>

<a href="./pdfs/Project_Report.pdf" download="My_Document.pdf">Download My PDF</a>


- to open enter the following twice: v23GhQkp#cBf!@P!

Project printout:[Personal Website Link](
- to open enter the following twice: 

For contact information visit my personal website: [Personal Website Link](https://alvg2.github.io/personal-website/)


......


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Force Download PDF</title>
</head>
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

            const pdfUrl = './pdfs/Project_Report.pdf'; // Use your correct relative path
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
</html>
