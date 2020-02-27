# Open Mail Relay Tester (MailTest)

MailTest is a penetration testing and red teaming tool that automates the testing of open mail relays.

## Installation

Clone the GitHub repository
```
git clone https://github.com/centralinfosec/Open-Mail-Relay-Tester /opt/Central-InfoSec/Open-Mail-Relay-Tester
```

## Usage

 - Update the email addresses and IP address in "/opt/Central-InfoSec/Open-Mail-Relay-Tester/testOpenMailRelay.sh"
 - Test the open mail relay by running one of the following commands:
    - e2e: external to external domain
    - e2i: external to internal domain
    - i2i: internal to internal domain
    - i2e: internal to external domain
```
chmod +x /opt/Central-InfoSec/Open-Mail-Relay-Tester/testOpenMailRelay.sh

/opt/Central-InfoSec/Open-Mail-Relay-Tester/testOpenMailRelay.sh e2e

/opt/Central-InfoSec/Open-Mail-Relay-Tester/testOpenMailRelay.sh e2i

/opt/Central-InfoSec/Open-Mail-Relay-Tester/testOpenMailRelay.sh i2i

/opt/Central-InfoSec/Open-Mail-Relay-Tester/testOpenMailRelay.sh i2e
```
