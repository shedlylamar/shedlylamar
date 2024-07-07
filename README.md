- 👋 Hi, I’m @shedlylamar
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
shedlylamar/shedlylamar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invoice Form</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="invoice">
        <!-- Space for Logo -->
        <div class="logo">
            <!-- Add your logo here -->
        </div>

        <h1>INVOICE</h1>

        <div class="business-info">
            <p><strong>Mailing Address:</strong> [Your Business Mailing Address]</p>
            <p><strong>Business Phone Number(s):</strong></p>
            <p>Phone: [Your Business Phone Number]</p>
            <p>Secondary Phone: [Your Secondary Phone Number]</p>
            <p><strong>Business Address:</strong> [Your Business Address]</p>
            <p><strong>Email Addresses:</strong></p>
            <p>Primary Email: [Your Primary Email Address]</p>
            <p>Secondary Email: [Your Secondary Email Address]</p>
        </div>

        <div class="customer-info">
            <p><strong>Customer Name:</strong> [Customer Name]</p>
            <p><strong>Address for Job:</strong> [Job Address]</p>
            <p><strong>Mailing Address:</strong> [Customer Mailing Address]</p>
            <p><strong>Phone Contact Numbers:</strong></p>
            <p>Primary Phone: [Customer Primary Phone Number]</p>
            <p>Secondary Phone: [Customer Secondary Phone Number]</p>
        </div>

        <div class="job-info">
            <p><strong>Salesperson:</strong> [Salesperson's Name]</p>
            <p><strong>Job Identification Number:</strong> [Job ID Number]</p>
            <p><strong>Terms of Purchase:</strong></p>
            <p>Down Payment: [Down Payment %]</p>
            <p>Balance Due Upon Completion: [Balance Due %]</p>
            <p><strong>Order Date:</strong> [Order Date]</p>
            <p><strong>Estimated Completion Day:</strong> [Estimated Completion Day]</p>
        </div>

        <table class="job-details">
            <thead>
                <tr>
                    <th>Quantity</th>
                    <th>Description</th>
                    <th>Unit Price</th>
                    <th>Total</th>
                </tr>
            </thead>
            <tbody>
                <!-- Repeat these rows as necessary -->
                <tr>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
                <!-- More rows -->
            </tbody>
        </table>

        <div class="notes">
            <p><strong>Notes:</strong></p>
            <textarea rows="10" cols="50">[Box for 250 words]</textarea>
        </div>

        <div class="additional-info">
            <p><strong>Additional Information:</strong></p>
            <textarea style="width: 100%; height: 3in; resize: none;">[Box 7" wide x 3" tall]</textarea>
        </div>
    </div>
</body>
</html>
CSS (styles.css):
css
Copy code
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.invoice {
    width: 8.5in;
    margin: 0 auto;
    padding: 1in;
    border: 1px solid #000;
}

.logo {
    text-align: center;
    margin-bottom: 1in;
}

h1 {
    text-align: center;
    font-size: 2em;
    margin-bottom: 1in;
}

.business-info, .customer-info, .job-info {
    margin-bottom: 1in;
}

p {
    margin: 0.2in 0;
}

.job-details {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 1in;
}

.job-details th, .job-details td {
    border: 1px solid #000;
    padding: 0.2in;
    text-align: left;
}

.notes textarea, .additional-info textarea {
    width: 100%;
    padding: 0.2in;
    font-size: 10pt;
    border: 1px solid #000;
    box-sizing: border-box;
}

.additional-info textarea {
    resize: none;
    overflow: auto;
}
