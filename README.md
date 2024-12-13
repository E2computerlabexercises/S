<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jonard D. Eva - Lab Exercises</title>
    <style>
        /* General Styling */
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #000033, #1e90ff);
            color: white;
            margin: 0;
            padding: 0;
        }
        /* Header */
        header {
            background-color: #00264d;
            text-align: center;
            padding: 20px;
            color: white;
        }
        header h1 {
            font-size: 2.5em;
            margin: 0;
        }
        header p {
            margin: 10px 0;
            font-size: 1.2em;
        }
        /* Navigation */
        nav {
            background: #003366;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            margin: 0 10px;
            font-size: 1.2em;
        }
        nav a:hover {
            background: #1e90ff;
            border-radius: 5px;
        }
        /* Main Content */
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 40px;
        }
        section h2 {
            border-left: 5px solid #1e90ff;
            padding-left: 10px;
            font-size: 1.8em;
        }
        img {
            max-width: 100%;
            border: 5px solid #1e90ff;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        audio, iframe {
            display: block;
            margin: 20px auto;
            max-width: 100%;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table th, table td {
            border: 1px solid #fff;
            padding: 15px;
            text-align: left;
        }
        table th {
            background: #1e90ff;
        }
        table tr:nth-child(even) {
            background: #003366;
        }
        form {
            background: #00264d;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }
        form label {
            font-size: 1.1em;
            margin-top: 10px;
            display: block;
        }
        form input, form select, form button {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            font-size: 1em;
            border: 1px solid #1e90ff;
            border-radius: 5px;
        }
        form input[type="radio"], form input[type="checkbox"] {
            width: auto;
        }
        /* Footer */
        footer {
            background: #000033;
            text-align: center;
            padding: 10px;
            color: white;
        }
    </style>
</head>

<body>
    <header>
        <h1>Jonard D. Eva</h1>
        <p>Section: II-India</p>
        <p>Hi Everyone! I am Jonard Eva, a Student from Sorsogon College of Criminology. This webpage includes my activities or LAB EXERCISES in E2-COMPUTER.</p>
    </header>
    <nav>
        <a href="#autobiography">Autobiography</a>
        <a href="#plagiarism">Plagiarism</a>
        <a href="#malware">Malware</a>
        <a href="#forms">Forms</a>
    </nav>
    <main>
        <!-- Autobiography Section -->
        <section id="autobiography">
            <h2>Autobiography</h2>
            <img src="https://via.placeholder.com/800x400" alt="Autobiography Image">
            <p>
                I was born in Prieto Diaz, Barangay Maningcay Di Oro. Growing up, I faced challenges, including living in the mountains for a year. 
                Despite hardships, I supported my family through farming and construction work, inspiring me to pursue my dream of becoming a police officer.
            </p>
            <h3>My Favorite Music</h3>
            <audio controls>
                <source src="videoplayback.webm" type="audio/webm">
                Your browser does not support the audio element.
            </audio>
        </section>
        <!-- Plagiarism Section -->
        <section id="plagiarism">
            <h2>Article: Plagiarism</h2>
            <p>
                Plagiarism is the unethical appropriation of another author's ideas or expressions without proper attribution. It can lead to consequences such as failing grades, academic probation, or expulsion.
                Practicing proper citation is essential to maintain academic integrity and respect intellectual property.
            </p>
        </section>
        <!-- Malware Section -->
        <section id="malware">
            <h2>Blog: Malware, Virus, Spam, and Antivirus</h2>
            <p><strong>What is malware?</strong> Malware refers to malicious software designed to harm or exploit devices and networks.</p>
            <table>
                <tr>
                    <th>What It Does</th>
                    <td>Antivirus software scans for and removes malicious software.</td>
                </tr>
                <tr>
                    <th>How It Works</th>
                    <td>It runs automatically in the background for real-time protection.</td>
                </tr>
                <tr>
                    <th>Benefits</th>
                    <td>Protects against viruses, spam, and malicious websites.</td>
                </tr>
                <tr>
                    <th>Examples</th>
                    <td>Microsoft Defender, Norton 360, Malwarebytes, McAfee.</td>
                </tr>
            </table>
            <h3>Informative Video</h3>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/QH3-Pq8EOfM" frameborder="0" allowfullscreen></iframe>
        </section>
        <!-- Forms Section -->
        <section id="forms">
            <h2>HTML Forms</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
                <label>Gender:</label>
                <input type="radio" id="male" name="gender" value="male"><label for="male">Male</label>
                <input type="radio" id="female" name="gender" value="female"><label for="female">Female</label>
                <label>Hobbies:</label>
                <input type="checkbox" id="reading" name="hobbies" value="Reading"><label for="reading">Reading</label>
                <input type="checkbox" id="traveling" name="hobbies" value="Traveling"><label for="traveling">Traveling</label>
                <label for="country">Country:</label>
                <select id="country" name="country">
                    <option value="Philippines">Philippines</option>
                    <option value="USA">USA</option>
                    <option value="India">India</option>
                </select>
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>
    
</body>

</html>
