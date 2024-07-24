<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feedback Form</title>
</head>
<body>
    <div class="bg-image"></div> 
    <div class="bg-text">
        <form method="post" action="#">
            <h1>Feedback Form</h1>
            <fieldset>
                <legend>Personal Information</legend>
                <table>
                    <tr>
                        <td>
                            <label for="name">Name: </label>
                        </td>
                        <td>
                            <input type="text" id="name" name="user_name" placeholder="Enter Your name">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <label for="address">Address: </label>
                        </td>
                        <td>
                            <input type="text" id="address" name="user_address" placeholder="Enter Your address">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <label for="email">Email: </label>
                        </td>
                        <td>
                            <input type="email" id="email" name="user_email" placeholder="Enter Your email here">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <label for="phone">Phone: </label>
                        </td>
                        <td>
                            <input type="tel" id="phone" name="user_phone" placeholder="Enter Contact Number">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <label for="gender">Gender</label>
                        </td>
                        <td>
                            <table>
                                <tr>
                                    <td>
                            <input type="radio" value="male" name="gender">                   
                         </td>
                         <td>
                            Male
                         </td>
                         </tr>
                         <tr>
                            <td>
                            <input type="radio" value="female" name="gender">                   
                         </td>
                         <td>
                            Female
                         </td>
                         </tr>
                         <tr>
                        <td>
                            <input type="radio" value="other" name="gender">                   
                         </td>
                         <td>
                            Other
                         </td>
                    </tr>
                    <tr>
                        <td>
                            <label for="dob">Date of Birth: </label>
                        </td>
                        <td>
                            <input type="date" value="dob" name="user_dob">
                        </td>
                    </tr>
                </table>
            </fieldset>

            <fileset>
                <div>
                    <label for="dept">Department:</label>
                    <select id="dropdown1">
                        <option value="dept1">Department #1</option>
                        <option value="dept2">Department #2</option>
                        <option value="dept3">Department #3</option>
                        <option value="dept4">Department #4</option>
                    </select>
                         &nbsp;  &nbsp;  &nbsp;  &nbsp;
                    <label for="status">Online Status</label>
                    <select id="dropdown2">
                    <option value="online">Online</option>
                    <option value="ofline">Ofline</option>
                </select>
                </div>
            </fileset>
            <fieldset>
                <legend>Your Feedback</legend>
                <div>
                    <textarea name="user_msg" id="msg" cols="40" rows="8" placeholder="Enter your message here"></textarea>
                </div>
            </fieldset>

            <div id="submitbutton">
                <button type="submit">Submit your Feedback</button>
            </div>
            </div>
        </form>
    </div>
</body>
</html>
