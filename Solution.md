HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Job Application Form</title>
</head>
<body>
  <header>
    <h1>Job Application Form</h1>
    <p>Fill out the details below to apply for an open role.</p>
  </header>

  <main>
    <form action="#" method="post">
      <div>
        <label for="applicant-name">Full Name</label>
        <input
          type="text"
          id="applicant-name"
          name="fullName"
          placeholder="Enter your full name"
          required
        >
      </div>

      <div>
        <label for="applicant-email">Email</label>
        <input
          type="email"
          id="applicant-email"
          name="email"
          placeholder="you@example.com"
          required
        >
      </div>

      <div>
        <label for="applicant-phone">Phone Number</label>
        <input
          type="tel"
          id="applicant-phone"
          name="phone"
          placeholder="+91 98765 43210"
          required
        >
      </div>

      <div>
        <label for="dob">Date of Birth</label>
        <input
          type="date"
          id="dob"
          name="dateOfBirth"
          required
        >
      </div>

      <div>
        <label for="portfolio-url">Portfolio URL</label>
        <input
          type="url"
          id="portfolio-url"
          name="portfolioUrl"
          placeholder="https://your-portfolio.example.com"
        >
      </div>

      <div>
        <label for="job-role">Job Role</label>
        <select id="job-role" name="jobRole" required>
          <option value="">-- Select a role --</option>
          <option value="frontend-intern">Frontend Developer Intern</option>
          <option value="junior-web-dev">Junior Web Developer</option>
          <option value="qa-analyst">QA &amp; Accessibility Tester</option>
          <option value="technical-writer">Technical Documentation Writer</option>
        </select>
      </div>

      <fieldset>
        <legend>Preferred Shift</legend>
        <div>
          <input type="radio" id="shift-day" name="preferredShift" value="day" required>
          <label for="shift-day">Day Shift</label>
        </div>
        <div>
          <input type="radio" id="shift-flexible" name="preferredShift" value="flexible">
          <label for="shift-flexible">Flexible Shift</label>
        </div>
        <div>
          <input type="radio" id="shift-evening" name="preferredShift" value="evening">
          <label for="shift-evening">Evening Shift</label>
        </div>
      </fieldset>

      <fieldset>
        <legend>Skills</legend>
        <div>
          <input type="checkbox" id="skill-html" name="skills" value="html">
          <label for="skill-html">HTML5 &amp; Semantic Markup</label>
        </div>
        <div>
          <input type="checkbox" id="skill-css" name="skills" value="css">
          <label for="skill-css">CSS Fundamentals</label>
        </div>
        <div>
          <input type="checkbox" id="skill-js" name="skills" value="javascript">
          <label for="skill-js">JavaScript Basics</label>
        </div>
        <div>
          <input type="checkbox" id="skill-git" name="skills" value="git">
          <label for="skill-git">Git &amp; GitHub</label>
        </div>
      </fieldset>

      <div>
        <label for="cover-letter">Cover Letter</label>
        <textarea
          id="cover-letter"
          name="coverLetter"
          rows="6"
          cols="50"
          placeholder="Tell us why you are a good fit for this role..."
          required
        ></textarea>
      </div>

      <div>
        <label for="referral-code">Referral Code (Disabled)</label>
        <input
          type="text"
          id="referral-code"
          name="referralCode"
          value="NOT-APPLICABLE"
          disabled
        >
      </div>

      <div>
        <button type="submit">Submit Application</button>
      </div>
    </form>
  </main>

  <footer>
    <p>&copy; 2026 Careers Portal</p>
  </footer>
</body>
</html>