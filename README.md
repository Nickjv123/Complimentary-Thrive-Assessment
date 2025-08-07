<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>City Fitness Thrive Assessment Signup</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #007BFF;
        }
        .logo {
            display: block;
            margin: 0 auto 20px;
            max-width: 200px;
        }
        form {
            max-width: 600px;
            margin: 0 auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        label {
            display: block;
            margin-top: 10px;
            font-weight: bold;
        }
        input[type="text"], input[type="email"], input[type="tel"], select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .waiver {
            border: 1px solid #ddd;
            padding: 10px;
            margin: 10px 0;
            max-height: 200px;
            overflow-y: auto;
            background: #fafafa;
        }
        button {
            display: block;
            width: 100%;
            padding: 10px;
            background: #28a745;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background: #218838;
        }
        .admin-note {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
            color: #555;
        }
    </style>
</head>
<body>
    <img src="https://cityfitness.com/wp-content/uploads/2025/07/Cf_Medallion_2007_Black_Background-scaled.png" alt="City Fitness Logo" class="logo">
    <h1>Sign Up for Complimentary Thrive Assessment</h1>
    
    <form id="signupForm" action="https://formspree.io/f/mldlobag" method="POST">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required>
        
        <label for="time">Preferred Time Slot:</label>
        <select id="time" name="time" required>
            <option value="">Select one</option>
            <option value="morning">Morning</option>
            <option value="afternoon">Afternoon</option>
            <option value="evening">Evening</option>
        </select>
        
        <label for="trainer">Trainer Preference:</label>
        <select id="trainer" name="trainer" required>
            <option value="">Select one</option>
            <option value="male">Male Trainer</option>
            <option value="female">Female Trainer</option>
            <option value="no-preference">No Preference</option>
        </select>
        
        <label>Waiver of Liability:</label>
        <div class="waiver">
            <p>THRIVE ASSESSMENT OVERVIEW</p>
            <p>The City Fitness Thrive Assessment is designed to establish a strong baseline for your fitness journey while addressing any injuries or discomfort. It includes an InBody scan to assess body composition, a movement screen to evaluate your mobility and stability, and a 60-minute workout tailored to your needs. Our program emphasizes "prehab" (injury prevention) and "rehab" (injury recovery) to keep you moving safely and effectively.</p>
            <p>WAIVER OF LIABILITY</p>
            <p>By signing up for a Complimentary Thrive Assessment at City Fitness, you agree to the following terms and conditions:</p>
            <ol>
                <li>You acknowledge that participation in the Thrive Assessment involves physical activity, which carries inherent risks of personal injury or discomfort.</li>
                <li>You declare yourself to be physically sound and not suffering from any condition, impairment, disease, or illness that would prevent your participation in the assessment or use of gym equipment.</li>
                <li>You agree to comply with all instructions provided by City Fitness trainers during the assessment, including proper use of equipment and adherence to safety guidelines.</li>
                <li>City Fitness, its employees, trainers, or affiliates are held harmless and released from any and all responsibility, liabilities, demands, or claims arising from your participation in the Thrive Assessment.</li>
                <li>You confirm that you are at least 18 years of age.</li>
                <li>You understand that this assessment is designed to evaluate your fitness level and provide recommendations, with an emphasis on prehab and rehab to keep you moving safely, and you participate voluntarily with knowledge of the risks involved.</li>
                <li>By signing below, you confirm that you have read and understood this Waiver of Liability and agree to its terms.</li>
            </ol>
            <p>Agreed by member electronically.</p>
        </div>
        
        <label>
            <input type="checkbox" id="agree" name="agree" required>
            I have read and agree to the Waiver of Liability above.
        </label>
        
        <button type="submit">Submit Signup</button>
    </form>
    <p class="admin-note">Submitted information can be accessed by City Fitness staff via the Formspree dashboard at <a href="https://formspree.io/dashboard">https://formspree.io/dashboard</a> (login required).</p>
</body>
</html>
