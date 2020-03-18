# google-colab-ssh

Connect to Google Colaboratory instance using SSH.

## Usage

First, generate an SSH key (`ssh-keygen -t rsa`) and create an [ngrok](https://ngrok.com/) account if you don't already have one.

Set the `ssh_key` and the `ngrok_token` at the beginning of the script and run it inside colab. It will output the command line to SSH into the machine.

Forked from [yashkumaratri](https://gist.github.com/yashkumaratri/204755a85977586cebbb58dc971496da)
