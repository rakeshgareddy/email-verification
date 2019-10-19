# email-verification
// import module
var truMail = require('trumail');

// Check if a email address exist or not
truMail.isValidEmail('abcd@gmail.com')
	.then(isValid => {
		// true if Valid
		// false if not
	});

// Check if a email address exist or not
truMail.getEmailInfo('abcd@gmail.com')
	.then(emailInfo => {
		console.log(emailInfo); //EMail details like username, host, deliverable etc.
	});
