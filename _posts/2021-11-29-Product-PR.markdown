---
layout: post
title:  "Product/Feature Press Release"

---

This is an attemp to write an example PR doc for a new feature (a practice followed at Amazon)

##### Heading:
Intelligent Compose (for Xmail currently) 
> short name for the product that the target customers will understand

##### Subheading: 
Write emails faster with Intelligent Compose in Xmail
> One sentence saying who the market is and what the benefit is

##### Summary:
The Intelligent Compose feature in Xmail uses Machine Learning to offer auto-complete suggestions for your emails as you type.
> 2–4 sentences that give a summary of the product and the benefits. Should be self-contained so that a person could read only this paragraph and still understand the new product/feature.

##### Problem: 
X number of emails are sent every day and we want to provide the best user experience. The current Intelligent Reply feature is used by y% of Xmail users. z% of these users don’t append anything to the suggested smart replies, whereas 100-z% of users draft a longer mail using smart reply as the base. For these 100-z% and 100-y% of users, we want to improve the writing process, thus hoping to improve the user experience. On average, a Xmail user repeats a sentence/phrase m times.
> 2–4 sentences describing the problem that a customer faces, which this product solves. Test your assumptions about the pain points that you are addressing.

##### Solution: 
Intelligent Compose offers suggestions that are tailored according to the user’s writing style, thus helping the user save time and also reducing spelling and grammatical errors. The suggestions are the results of a neural language learning model. Further, contextual information is also accounted for while offering suggestions. For example, if it’s a Friday evening, one of the suggestions towards the end of the mail could be “Have a nice weekend!”. 
> 2–4 sentences, describing how the new product/feature addresses this problem. Test your assumptions about how you are solving the pain points.

##### Getting started: 
Intelligent Compose is an account-level setting. By default, the user will automatically start getting suggestions (the setting for this feature will be turned on). When you see a suggestion that is appropriate, you can press “tab” to auto-complete and accept (on the desktop). On the mobile app, swipe right to add it to the email. 
> 1–3 sentences describing how someone can start using this product/feature (if it’s baked into the existing product, say this explicitly). Test your assumptions about how easy the ramp-up is for your customers to take advantage of the new product/feature.

##### Internal quote: 
“Being a non-native speaker, the suggestions help me reduce the grammatical errors. It also helps me to cut down my time on repetitive writing. We should also launch it across the workspace - some of the exciting use cases could be speaker notes in slides, comments in docs, etc.”  
> Someone within your company is being quoted about what they like about the product/feature. Test your assumptions about the value you are creating for your customers and how you position this product within your broader product offerings.

##### Customer Quote(s): 
“Intelligent Compose has helped me write high-quality content faster and more easily. Can’t wait to try it out on Docs!” <br/>
“The suggestions offered by Intelligent Compose seem quite natural and I end up accepting it 95% of the time!” 
> a hypothetical customer saying what they like about the new product/feature. Test your assumptions about how you want your customers to react to the new product/feature and your ideal customer profile. They should be doing something that they couldn’t do before, doing something much quicker and easier, saving time and effort, or in some other way making their life better. Whatever the benefit is, their delight in the benefit(s) should be exhibited in the quote. This should be multiple quotes from different customers if you have multiple profiles of ideal customers, for example, mid-market and F50 customers.

##### Call to action: 
Over the next few days, Xmail users would start receiving these suggestions. It would be enabled for the X-suite users in the coming weeks. This is currently available to users whose primary language is set as English. 
> 1–2 sentences telling the reader where they can go next to start using the product/feature. Tests your assumptions about whether this is a feature that is automatically on, something they need to turn on, a beta-release, etc.

### FAQs
> A set of public frequently-asked questions and their answers. This should be a comprehensive list of everything that a customer might want to know about the product. It should include any reasonable question that comes up when discussing the new product/feature with customers and customer-facing teams during the development of the product/feature.

#### Q. How does Xmail uses my data
Xmail removes all the personal and sensitive data before training the model. Your data is only used to develop a writing style, personalized and unique to you, and the suggestions based on this model are not shown to anyone else. Further, people working on this project do not have access to the raw content of the mails. 

### Internal FAQs
> A set of private, internal frequently-asked questions and their answers in a format that can be understood by every other stakeholder. An FAQ might include wireframes of a product with a strong UX component, or a link to separate wireframe documents, but the PR should rely on text alone. This will allow all internal stakeholders to get clarity on the product/feature. 

#### Q. Wireframe/mock 
Link here

#### Q. What are some of the challenges anticipated
- Privacy: Personal data should not appear in the suggestions for the user itself/any other user. People working on the feature should not be able to see the information as well. 
- Personalization: Each user has a unique writing style which should be considered for
- Latency: Since the suggestions would  be offered post each key-stroke(?), the order for results should be in milliseconds

#### Q. How would we measure the success of this feature (after launch)
- CTR on auto-complete
- Words/characters not typed as % of the content of the mail (Equivalent time saved) 
Other relevant metric:
- % of users turning off the Intelligent Compose feature in the settings

#### Q. Tech-questions - What model is being used 
- Global model 
- User-level model for personalization
- Multi-lingual models
- A mix of all these 

#### Q. Trade-offs/Decisions taken 
- We only show suggestions when the output crosses the threshold/confidence score 
- Context parameters: previous emails in the thread, subject and time of the day will be used to offer more appropriate suggestions. 

This post is inspired by the [Coda template](https://coda.io/@productschool/product-launch-template/press-release-4)
