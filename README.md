
# CHAT BOT

[![forthebadge](https://forthebadge.com/images/badges/uses-html.svg)](https://forthebadge.com)

[![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com)

chatbot to talk with bots

## To start

 - git clone
 - start index.html

### Structure
```bash
.
├── README.md
├── assets
├── css
│   ├── index.css
│   ├── lib
│   │   └── bootstrap.min.css
│   └── reset.css
└── index.html
```

### Components

- Contact:

Component used to display contacts
```html
<div class="contacts">
        <!-- Profiles -->
        <div class="contacts--profiles">
          <div class="contacts--profiles-avatar">
            <img src="https://ih1.redbubble.net/image.617355277.4370/poster,504x498,f8f8f8-pad,600x600,f8f8f8.u1.jpg" alt="avatar" />
          </div>
          <div class="contacts--profiles-name">
            <span>Tyrion Lannister</span>
          </div>
        </div>
        <!-- List -->
        <div class="contacts--list">
          <ul>
            <li>
              <div class="contacts--list-item">
                <div class="contacts--list-item-avatar">
                  <img src="https://tel.img.pmdstatic.net/fit/https.3A.2F.2Fprd2-tel-epg-img.2Es3-eu-west-1.2Eamazonaws.2Ecom.2FproviderPerson.2F70635f1576fb02de.2Ejpeg/300x300/quality/80/sansa-stark.jpeg" alt="avatar" />
                </div>
                <div class="contacts--list-item-name">
                  <span>Sansa Stark</span>
                </div>
                <div class="contacts--list-item-counter">
                  <span>32</span>
                </div>
              </div>
            </li>
            <li>
```

- Message:
Component used to display conversations between contacts

  - message bubble:
  ```html
            <div class="messages--received">
            <div class="messages--received-status">
              <div class="messages--received-status-avatar">
                <img src="https://tel.img.pmdstatic.net/fit/https.3A.2F.2Fprd2-tel-epg-img.2Es3-eu-west-1.2Eamazonaws.2Ecom.2FproviderPerson.2F70635f1576fb02de.2Ejpeg/300x300/quality/80/sansa-stark.jpeg" alt="avatar" class="imgmessage" />
              </div>
              <div class="messages--received-status-name">
                <span>Sansa Stark</span>
              </div>
              <div class="messages--received-status-date">
                <span>16:04:54</span>
              </div>
            </div>
            <div class="messages--received-text">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ac libero eget mi molestie tempus id ac tortor. Pellentesque ullamcorper arcu orci, eu bibendum ligula iaculis et</p>
            </div>
          </div>

- Typping message:
Component used to type our messages

```htlm
        <div class="typping">
          <form action="get">
            <input type="text" class="css-input" placeholder="Taper un message" />
            <input type="submit"/>
          </form>
        </div>
```




## Made with

* HTML5
* CSS3
* [Sublime Text](https://www.sublimetext.com/) - Editeur de textes


## Author

* **Louis Gregory** _alias_ [@taurouf](https://github.com/taurouf)
