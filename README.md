# Timestamp Date API
Node.js API that returns the Unix timestamp and UTC date string of a given date or the current date if none is provided.

*FCC - Back End Development and APIs Projects #1*
## Getting started
1. Clone the repository:
```bash
git clone https://github.com/jlopezestrada/Timestamp-Microservice.git
```
2. Install the dependencies:
```bash
npm install
```
3. Start the server:
```
npm start
```
## Usage
Append the date in Unix timestamp or date string format to the /api/ endpoint:
```bash
/api/1683794482511
```
The server will respond with a JSON object containing the Unix timestamp and UTC date string:
```json
{
  "unix": 1683794482511,
  "utc": "Thu, 11 May 2023 08:41:22 GMT"
}
```
