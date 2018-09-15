# CONFIGURING SDU E-MAIL WITH MUTT

Configuring SDU e-mail to be able to open it, read and send mails form the command line in Ubuntu. Mutt is a small but very powerful text-based mail client for Unix operating systems.

For tutorials and man pages visit [Mutt's website](http://www.mutt.org/)

#### Installing mutt:

```sh
$ sudo apt-get install mutt
```

#### Configuration for SDU-account

There are two configuration files in the repo. __muttrc__ contains the credentials and basic confuguration data, while __mailcap__ is just for dealing with HTML emails. Download this repo and edit the __muttrc__ file in the fields indicated in the comments.

```sh
$ git clone <repo url>
$ vim muttrc
$ cp muttrc ~/.muttrc
$ cp mailcap ~/.mailcap
```

#### Verification

To verify that everything is working enter mutt by the command:

```sh
$ mutt
```

Check that the INBOX is working. Then, to compose and send a test mail type m in the main menu and start following indications displayd on top of the mutt interface.
