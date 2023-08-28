# Smahh_Nezox
Cyber Security Website for Smahh
Introduction
Nezox is a Responsive and Clean React Next.js template created for Cyber Security Services Company and independent security services providers. The template is offering 5+ homepage variations design with a blog, blog details other inner pages. It looks beautifully stunning on all types of screens and devices including Windows, Mac, iOS, Android, etc. This has been built with React JS, Next.js, Sass, and Bootstrap 5.x.

Setup Development Environment
To kickstart the development of the web app with Nezox, at first need to setup the react development environment.

Following tools are needed to setup a react dev environment:

Node JS
NodeJS works as a node package manager behind the scene. It is recommended to download and install the latest version of Node JS from its official site https://nodejs.org/en/

Preparation
You'll need to install Node.js >=v14.17+ (Recommended Version) (NPM comes along with it) and serve (an NPM package)

Use command line tool i.e. PowerShell or terminal and navigate to the project(Nezox) root. This is PowerShell in windows and terminal on mac/linux.

Let's have a look on the setup process:
Use terminal and navigate to the project root.

Then run : npm install

Then run : npm run dev

It'll return something like this in the console:

> project@1.4.0 dev drive:\project

> next

[ wait ] starting the development server ...

[ ready ] started server on http://localhost:3000 ...

[ event ] compiled successfully

Now, in the browser go to localhost:3000

For Production Build
Run : npm run build

Then Run : npm run start

See the official next.js doc here

Pages and Components Info
Home Demo 1 (/pages/index.js)
Home Demo 2 (/pages/index2.js)
Home Demo 3 (/pages/index3.js)
Home Demo 4 (/pages/index4.js)
Home Demo 5 (/pages/index5.js)
About Us (/pages/about-us.js)
Blog Style One (/pages/blog-1.js)
Blog Style Two (/pages/blog-2.js)
Blog Style Three (/pages/blog-3.js)
Blog Details (/pages/blog-details.js)
Coming Soon (/pages/coming-soon.js)
Contact (/pages/contact.js)
FAQ (/pages/faq.js)
Login (/pages/log-in.js)
My Account (/pages/my-account.js)
Pricing (/pages/pricing.js)
Privacy Policy (/pages/privacy-policy.js)
Recover Password (/pages/recover-password.js)
Register (/pages/register.js)
Services Details (/pages/services-details.js)
Services Style One (/pages/services-style-one.js)
Services Style Two (/pages/services-style-two.js)
Services Style Three (/pages/services-style-Three.js)
Solutions (/pages/solutions.js)
Solution Details (/pages/solution-details.js)
Team (/pages/team.js)
Terms Conditions (/pages/terms-conditions.js)
Testimonials (/pages/testimonials.js)
Etc....
Common Components:
Navbar (/components/_App/Navbar.js)
NavbarTwo (/components/_App/NavbarTwo.js)
NavbarThree (/components/_App/NavbarThree.js)
NavbarFour (/components/_App/NavbarFour.js)
NavbarFive (/components/_App/NavbarFive.js)
TopHeader (/components/_App/TopHeader.js)
TopHeader Two (/components/_App/TopHeaderTwo.js)
TopHeader Three (/components/_App/TopHeaderThree.js)
Layout (/components/_App/Layout.js)
Footer (/components/_App/Footer.js)
GoTop (/components/_App/GoTop.js)
GetIn Touch Form (/components/_App/GetInTouchForm.js)
GetIn Touch Form Two (/components/_App/GetInTouchFormTwo.js)
Latest News (/components/_App/LatestNews.js)
Latest News Two (/components/_App/LatestNewsTwo.js)
Our Challenges (/components/_App/OurChallenges.js)
Page Banner (/components/_App/PageBanner.js)
Partners (/components/_App/Partners.js)
Partners (/components/_App/Partners.js)
Partners Two (/components/_App/PartnersTwo.js)
Price Table (/components/_App/PriceTable.js)
Price Table Two (/components/_App/PriceTableTwo.js)
Team Member (/components/_App/TeamMember.js)
Team Member Two (/components/_App/TeamMemberTwo.js)
Testimonials (/components/_App/Testimonials.js)
Template Features:
ES6+
React JS 17+
Next JS 12+
Bootstrap v5.x
Simple client-side routing (page based)
Easy Customization
React Modal Video
Dependencies
Here are the dependencies list which being used in the Nezox React Template:

"dependencies": {
	"axios": "^0.21.4",
    "next": "^12.0.4",
    "nodemailer": "^6.7.1",
    "nodemailer-sendgrid-transport": "^0.2.0",
    "react": "^17.0.2",
    "react-accessible-accordion": "^3.3.5",
    "react-dom": "^17.0.2",
    "react-hook-form": "^6.15.8",
    "react-modal-video": "^1.2.8",
    "react-owl-carousel3": "^2.2.5",
    "react-tabs": "^3.2.3",
    "sass": "^1.43.4",
    "sweetalert2": "^10.16.9",
    "sweetalert2-react-content": "^3.3.3"
}

Change Default Home Page
The default home page is index.js which placed in /pages/index.js if you want to change this default to home page two as default home then just take backup your index.js & make home-two.js to index.js & that is.

RTL Style
Following by the screenshot comment out the rtl.css file path

![image](https://github.com/juanmibro/Smahh_Nezox/assets/22509565/028bffdd-d2d2-4b5b-bfb7-68c320de4881)

Fonts Used
By default, the template loads Oswald & Open Sans font from Google Web Font Services, you can change the font with the one that suits you best. Google Fonts

You will find the font code in the "style.scss file: public/css/style.scss

  @import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,300;0,400;0,700;0,900;1,300;1,400&display=swap');

  $body-family: 'Lato', sans-serif;

Note: After SCSS file run then it will be work

How to Run The SCSS File
Please open the file Visual Studio Code Editor. And follow the video tutorial.

Here the Link: https://www.youtube.com/watch?v=0MWmv1Gvv5w

Contact Form Setup
Please create the SendGrid API key follow the below link:
https://sendgrid.com/docs/ui/account-and-settings/api-keys/

Please follow the screenshot instruction file path: pages/api/contact.js

![image](https://github.com/juanmibro/Smahh_Nezox/assets/22509565/b94e477d-284c-4fac-a59e-e3c4510980a4)

Following by the screenshot update the baseUrl

![image](https://github.com/juanmibro/Smahh_Nezox/assets/22509565/4a8b986c-c2c8-4dd6-8d65-46baf67ae378)

How to off Preloader

Please remove or comment the below code file path: components/_App/Layout.js

![image](https://github.com/juanmibro/Smahh_Nezox/assets/22509565/07829251-ca08-439a-a8f7-7fb3b8315520)

Credits
Images
Unsplash
Burst
Freepick
Packages
React
Next.js
ReactDom
Bootstrap
ES6-Promise
react-modal-video
Google Fonts




