# Google Cloud Event Certificate Generator

This repo simply use a template certificate docx file and generates certificates
both docx and pdf.

### Working on Windows only.

## Run these 4 commands in your terminal

```
git clone https://github.com/DevanshKapri/Cloud-Certificate-Generator.git
cd GCP-Certificate
```

Now Copy your progress report to the Data Folder and rename it as `ParticipantList.csv`

```
pip install -r requirements.txt
python main_certificate.py
```

## Customization

- You can change the certificate template file in the `Data` folder.
- You can change the email template file in the `Data` folder.

## How to send emails?

- You can use the `Mail.xlms` file to send emails to the participants. Open this with Excel. Press `Allow Content` if required.
- Do not need to change anything in the file itself.
- All you need to do is to search for `View Macros` in excel and then select the `Send_Mails` macro and then click on `Run`.
- Now open outlook and login.
- Click on outbox and see the mails being sent one by one.

## Further Releases (Planning)

- Implementing for Linux users?

<h2></h2>
