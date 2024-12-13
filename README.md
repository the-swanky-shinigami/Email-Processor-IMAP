# Email-Processor-IMAP
This Python project connects to an email server, retrieves unread emails, processes them to extract key details (sender, subject, timestamp), and stores the information in a SQLite database.

Features

* Connects to an IMAP email server (tested with Gmail).

* Retrieves unread emails and marks them as read after processing.

* Extracts the sender, subject, and timestamp of each email.

* Stores email details in a local SQLite database (```emails.db```).

* Logs processed emails and any errors encountered during execution in a log file (```email_processor.log```).

* Implements retry logic to handle transient failures during connection or email processing.

Installation

1. Clone the repository:

```
git clone https://github.com/the-swanky-shinigami/Email-Processor-IMAP.git
cd email_processor_imap
```

2. Install necessary dependencies:

```
pip install pandas
```

3. Ensure your Gmail account is set up to allow IMAP and third-party apps. Create an app password for secure login.

Usage

In the ```main()``` function, replace the placeholder credentials with your Gmail username and app password and run everyhing.
