# send_sms
🌐 Send SMS with the help of Ansible 🌐

Introduction:
The intelligence and the power of Ansible can be used to send automated sms

Requirements:
- Ansible installed in controller node
- Knowledge of Ansible
- Account created in Twilio

Tasks:
- Signup for twilio account: https://lnkd.in/gZfB9Hae
- Once your account is completely ready, choose the "messaging" service
- Once this is done, create your twilio phone number which will be used to send sms
- Keep your account_sid, auth_token and the twilio phone number handy.
- Login to controller node and install the collection community.general:
ansible-galaxy collection install community.general
- Once it is successful, write the playbook with community.general.twilio module (see the screenshot attached).
- If everything is done properly, the message will be sent successfully in recipient's contact number.
