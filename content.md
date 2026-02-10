Directions:
Do research about making an html email signature for microsoft outlook. We need to account for everything.

How should we handle image sizes so they appear are correct size.

How should CSS be handled so it works in outlook.
- Links should not be underlined. and appear as normal text.


content:

name: Myleas Williams

title: Senior Contract Administrator (Corporate Service)
phone: +1 (608) 628-8598
email: mwilliams@terrapower.com

terrapower.com

logo: /assets/terrapower-logo.png

social icons:
- name: LinkedIn
  url: https://www.linkedin.com/company/terrapower/
  icon: /assets/linkedin-logo.png
- name: X
  url: https://twitter.com/terrapower
  icon: /assets/x-logo.png

legal info:
This message may contain confidential information. If you are not the intended recipient of the message, please destroy it. Any unauthorized dissemination, distribution or copying of the material in this message, and any attachment to the message, is strictly forbidden.

Email width: 520px

``` css
.name {
color: #62B73D;
font-family: Arial;
font-size: 17px;
font-style: normal;
font-weight: 700;
line-height: 21px; /* 123.529% */
}
.title {
color: #0B131B;
font-family: Arial;
font-size: 14px;
font-style: normal;
font-weight: 700;
line-height: 21px;
}

.email,
.phone {
color: #0B131B;
font-family: Arial;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 21px;
}

.website {
color: #62B73D;
font-family: Arial;
font-size: 14px;
font-style: normal;
font-weight: 700;
line-height: 21px;
}

.line {
width: 520px;
height: 0.5px;
background: #808080;
}

.legal-info {
color: #000;
font-family: Arial;
font-size: 10px;
font-style: italic;
font-weight: 400;
line-height: 13px; /* 130% */
}


```