# Email-Processor-IMAP
This Python project connects to an email server, retrieves unread emails, processes them to extract key details (sender, subject, timestamp), and stores the information in a SQLite database.

Features

* Connects to an IMAP email server (tested with Gmail).

* Retrieves unread emails and marks them as read after processing.

* Extracts the sender, subject, and timestamp of each email.

* Stores email details in a local SQLite database (emails.db).

* Logs processed emails and any errors encountered during execution in a log file (email_processor.log).

* Implements retry logic to handle transient failures during connection or email processing.

Installation

Clone the repository:

'''
git clone https://github.com/your-username/email-processor-with-retry.git
cd email-processor-with-retry
'''

Install necessary dependencies:

pip install pandas

Ensure your Gmail account is set up to allow IMAP and third-party apps. Create an app password for secure login.
