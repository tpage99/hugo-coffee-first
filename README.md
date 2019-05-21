# 👨‍💻 Hugo with Snipcart

This is a demo site made with the static site generator (SSG) [Hugo](https://gohugo.io/), utilizing [Forestry.io](https://forestry.io/) as a content management system (CMS), and [Snipcart](https://snipcart.com/) - an ecommerce platform that includes checkout and payment gateways. 

## 😕 The Problem 

We need a fast and secure site that's easy enough to update/maintain for non-technical users. Previously Wordpress was the go-to for this sort of situation. And while it is relatively easy even for non-technical users to update content, Wordpress is just too slow, security-issue-prone, and can be too complex for most users. Sites written in pure HTML, CSS, and Javascript (the language of the web) can be very fast and very secure, but could prove to be difficult for users to update content (such as new items in an ecommerce website). Templating updates can prove difficult/time-consuming for developers as well if there are changes to a header or footer for updated contact information or a new logo.  

## 💡 The Solution

Enter Hugo. An SSG written in Go that has ridiculously fast build times. Utilizing Forestry.io as our CMS to update store items and Snipcart for our shopping cart and payment method, we now had a fast and secure website that can be updated regularly and simply by users who don't even have coding knowledge. 

## 🏃‍ The Steps


### Step 1. Clone the repo

```sh
git clone https://github.com/tpage99/hugo-coffee-first.git
```

### Step 2. npm install

```sh
npm install
```

### Step 3. to run locally

```sh
hugo server
```

*if there's anything still in draft form you need to append* `-D` *to the command so that draft form items show up*

### Step 4. Be awesome

😎

## Resources
[Hugo with Snipcart Tutorial](https://snipcart.com/blog/hugo-tutorial-static-site-ecommerce)

[Hugo Docs](https://gohugo.io/documentation/)

[Forestry.io Docs](https://forestry.io/docs/welcome/)