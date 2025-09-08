<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Registration Form</title>
</head>
<body>
    <main>
        <article>
            <section>
                <h2>User Registration Form</h2>
                <form action="/submit"method="post"id="userregistrationform">
                    <fieldset>
                        <legend>Personal Information</legend>
                        <div class="form group">
                            <p>
                            <label for="firstname">First Name:</label>
                            <input type="text" id="Fistname" name="firstname"  placeholder="Enter your first name">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label for="lastname">Last Name:</label>
                            <input type="text" id="Lastname" name="Lastname"  placeholder="Enter your last name">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label for="birthdate">Date of Birth:</label>
                            <input type="datetime-local" id=" birthdate" name="birthdate">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label for="Age">Age:</label>
                            <input type="number" id=" age" name="age" min="18" max="60">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label for="gender">Gender:</label>
                             </p>
                        </div>
                        <div class="form-group">
                            <input type="radio" id=" gender" name="gender">
                            <label>Male</label>
                                </div>
                        <div class="form-group">
                            <input type="radio" id=" gender" name="gender">
                            <label>Female</label>
                        </div>
                        <div class="form group">
                            <p>
                            <label for="profile photo">Profile photo:</label>
                            <input type="file" id="choosefile" name="profile photo">
                            </p>
                        </div>
                    </fieldset>
                    <fieldset>
                        <legend>Contact & Address Information</legend>
                        <div class="form group">
                            <p>
                            <label for="email">Email Address</label>
                            <input type="email" id="email" name="email" placeholder="your@email.com">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label>Phone Number:</label>
                            <input type="number" id="phonenumber" name="phonenumber">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label>Personal Website:</label>
                            <input type="text" id="personalwebsite" name="personalwebsite" placeholder="https://example.com">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label>Street Address:</label>
                            <input type="text" id="Address" name="Address">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label>City:</label>
                            <input type="text" id="City" name="City">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label for="Country">Country:</label>
                            <select id="Country"name="Country">
                                <option value="">Select a Country</option>
                                <optgroup label="Africa">
                                    <option value="ke">Kenya</option>
                                    <option value="Ug">Uganda</option>
                                    <option value="Tz>">Tanzania</option>
                                </optgroup>
                                <optgroup label=" North America">
                                    <option value="Us">Unted States</option>
                                    <option value="ca">Canada</option>
                                </optgroup>
                                <optgroup label="Europe">
                                    <option value="uk">United Kingdom</option>
                                    <option value="fr">France</option>
                                </optgroup>
                            </select>
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label for="postal code">ZIP/Postal Code:</label>
                            <input type="text" id="postal" name="postal">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label for="contact time">Preferred Contact Time:</label>
                            <input type="text" id="time" name="time">
                            </p>
                        </div>
                    </fieldset>
                    <fieldset>
                        <legend>Preferences & Inerests</legend>
                        <div class="form group">
                            <p>
                            <label>Favourite Color:</label>
                            <input type="color" id="color" name="color">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label>Experience Level(1-10):</label>
                            <input type="range" id="Experience" name="Experience">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label>Birth Month:</label>
                            <input type="month" id="birthmonth" name="birthmonth">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label>Available Week:</label>
                            <input type="week" id="availableweek" name="availableweek">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label>Search Keyword</label>
                             <input type="text" id="keyword" name="keyword" placeholder="Enter Keywords...">
                            </p>
                        </div>
                        <div class="form group">
                            <p>
                            <label>Ineterests(Select all that apply)</label>
                        </div>
                        <div class="form group">
                            <input type="checkbox" id="Technology" name="Technology">
                            <label>Technology</label>
                        </div>
                        <div class="form group">
                            <input type="checkbox" id="Sports" name="Sports">
                            <label>Sports</label>
                        </div>
                        <div class="fprm group">
                            <input type="checkbox" id="Music" name="Music">
                            <label>Music</label>
                        </div>
                        <div class="form group">
                            <input type="checkbox" id="Reading" name="Reading">
                            <label>Reading</label>
                        </div>
                        <div class="form group">
                            <input type="checkbox" id="Cooking" name="Cooking">
                            <label>Cooking</label>
                        </div>
                        </p>
                         <p>
                            <label>Education Level:</label>
                            <select>
                                <option value="Select Education Level">Select Education Level</option>
                                <option value="Masters">Masters</option>
                                <option value="phd">Phd</option>
                                <option value="degree">Bachelors Degree</option>
                                <option value="dip">Diploma</option>
                                <option value="Cert">Certificate</option>
                                <option value="highschool">Highschool</option>
                            </select>
                         </p>
                        </div>
                        <div class="form group">
                            <p>
                                <label>Create Password:</label>
                                <input type="text" id="Password">
                            </p>
                        </div>
                        <div class="form-group">
                            <p>
                                <label>Confirm Password</label>
                                <input type="text" id="password">
                            </p>
                        </div>
                    </fieldset>
                    <fieldset>
                        <legend>Feedback & Additional Information</legend>
                             <div class="form group">
                                <label>Tell us about yourself:</label>
                               <p>
                                <textarea name="bio" rows="4"Cols="50">Write a brief description about yourself...</textarea>
                               </p>
                            </div>
                            <div class="form group">
                            <label>Suggestions for improvement:</label>
                               <p>
                                <textarea name="suggestions" rows="4"Cols="50">Any suggestions or feedback...</textarea>
                               </p>
                            </div>
                            <div class="form group">
                                <p>
                                    <label>Registration Date & Time:</label>
                                    <input type="datetime-local" id="Registrationdate" name="Registrationdate">
                                </p>
                            </div>
                            <div class="form group">
                                <p>
                                    <label>How did you hear about us?</label>
                                    <select>
                                        <option value="">Select Source</option>
                                        <option value="Linkedin">Linkedin</option>
                                        <option value="Twitter">Twitter</option>
                                        <option value="Facebook">Facebook</option>
                                        <option value="Other">Other</option>
                                    </select>
                                </p>
                            </div>
                            <div class="form group>">
                                <p>
                                    <label>Upload Resume(Optional):</label>
                                    <input type="file" id="Resume" name="Resume">
                                </p>
                            </div>
                            <div class="form group">
                                <p>
                                    <input type="checkbox" id="newsletter" name="newsletter">
                                    <label>Subscribe to our newsletter</label>
                                      </p>
                            </div>
                            <div class="form group">
                                <p>
                                    <input type="checkbox" id="Terms" name="Terms">
                                    <label>I agree to the Terms and Conditions</label>
                                </p>
                            </div>
                            <div class="form group">
                                <p>
                                    <input type="checkbox" id="Policy" name="Policy">
                                    <label>I agree to the Privacy Policy</label>
                                </p>
                            </div>      
                    </fieldset>
                    <fieldset>
                        <div class="form-group">
                            <button type="submit">Register</button>
                            <button type="clear">Clear Form</button>
                        </div>
                    </fieldset>
                </form>
            </section>
        </article>
    </main>
</body>
</html>
