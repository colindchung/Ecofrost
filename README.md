# [Ecofrost Heating and Cooling](https://ecofrostheating.com/)

Ecofrost Heating and Cooling is a local business in the GTA who distributes and installs HVAC (heating, ventilation and air conditioning) units to customers across Ontario. Over the COVID-19 pandemic, they were in need of a basic [business website](https://www.ecofrostheating.com/) to generate leads in the new online world.

## Design
As the only developer on the team, a lot of the design choices were left to me. Below are some of the high level design decisions for this website.

### Backend
Backend design for this website is very simple. Each HVAC unit has a corresponding product page (see [example](https://www.ecofrostheating.com/furnace/lennox/p/ml196uh045xe24b)) and this data is captured in a JSON. MongoDB was the database of choice due to its document-oriented nature and ease of use.

### Search Engine Optimization
As a small local business, search engine optimization to improve appearances on Google search results is highly important and incurring hefty advertising costs is not always feasible. Next.js was used as the frontend framework to easily implement server side rendering. Mobile responsiveness and performance were also areas of focus, as well as maximizing the number of backlinks, keywords and configuring HTTPS.


## Technologies and tools
Listed below are some of the tools and technologies that were used in constructing this product.

### Frontend
- [Figma](https://www.figma.com/)
- [Next.js](https://nextjs.org/)
- [React.js](https://reactjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Google reCAPTCHA](https://www.google.com/recaptcha/about/)

### Backend
- [Node.js (TypeScript)](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Docker](https://www.docker.com/)
- [Google reCAPTCHA](https://www.google.com/recaptcha/about/)
- [PayPal Developer](https://developer.paypal.com/home/)

### Infrastructure
- [Amazon Web Services](https://aws.amazon.com/)
	- Elastic Beanstalk
	- CodePipeline
	- Route53
	- AWS Certificate Manager
	- Cognito
- [Docker](https://www.docker.com/)
- [Netlify](https://www.netlify.com/)
- [Google Search Console](https://search.google.com/search-console/welcome)
- [Google Domains](https://domains.google.com)
