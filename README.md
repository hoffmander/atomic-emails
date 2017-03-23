# Email System MJML

This is a blue-print design system based off of Atomic Design using the MJML framework to create a sustainable, reliable and consistent system for developing responsive email templates. 

* [Atomic Design](http://bradfrost.com/blog/post/atomic-web-design/)
* [MJML Framework](https://mjml.io/)

## Install MJML

Follow the instructions to install MJML, you can find it their documentation or on their [MJML Git Repo](https://github.com/mjmlio/mjml). MJML Requires [Node.js](https://nodejs.org/en/) and I highly recommend using their syntax libraries for [Sublime](https://github.com/mjmlio/mjml-syntax) and [Atom](https://atom.io/packages/language-mjml).

# Atomic Design for Emails

While Atmoic Design was originally intended for the web, it's also true that the same concept can be applied for a mobile app, so what not for emails? :boom: But let's be real, not all the same components are shared between the two and also building a pattern lab or style guide inside MJML presents some of it's own challenges. But let's start out by listing all the atoms, then molecules, organisms, and templates and finally instead of pages, I'm going to call them what they are, emails.

## Atoms 

Let's be honest, emails don't need to be complicated. Instead of listing every single element I can think of, I'm going to only inclue the ones that I will actually be used. So in some ways this will be opinionated, if there's something I left out, feel free to make a pull request :kissing_smiling_eyes:

### Colors
* Brand Colors
* Neutral Colors
* Utility Colors

### Typography
* Fonts
* Headlines
* Horizontal Rule

#### Inline Elemets
* Text Link
* Strong
* Emphasis
* Underline
* Striketough
* Small
* Paragraph