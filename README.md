
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 500px;
            margin: 0 auto;
            padding: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        input[type="tel"],
        input[type="date"],
        select {
            width: 100%;
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
        }
        .gender-options {
            display: flex;
            gap: 15px;
        }
        .gender-option {
            display: flex;
            align-items: center;
        }
        .gender-option input {
            margin-right: 5px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <form>
        <div class="form-group">
            <label for="username">User Name:</label>
            <input type="text" id="username" name="username" value="User Name">
        </div>
        
        <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" value="abc@mail.com">
        </div>
        
        <div class="form-group">
            <label for="phone">Phone:</label>
            <input type="tel" id="phone" name="phone" value="+923338503885">
        </div>
        
        <div class="form-group">
            <label>Gender:</label>
            <div class="gender-options">
                <div class="gender-option">
                    <input type="radio" id="male" name="gender" value="male">
                    <label for="male">Male</label>
                </div>
                <div class="gender-option">
                    <input type="radio" id="female" name="gender" value="female">
                    <label for="female">Female</label>
                </div>
            </div>
        </div>
        
        <div class="form-group">
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob">
        </div>
        
        <div class="form-group">
            <label for="degree">Degree:</label>
            <select id="degree" name="degree">
                <option value="BS" selected>BS</option>
                <option value="MS">MS</option>
                <option value="PhD">PhD</option>
                <option value="Other">Other</option>
            </select>
        </div>
        
        <button type="submit">Submit</button>
    </form>
</body>
</html>