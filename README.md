Live Link: [core-dev-ltd](https://ephemeral-kitten-3b272d.netlify.app/)

- It was export in the coming soon component. That's why it gives an error and I have just added export default so that the functional component can be exported by default.
- In counter.js the end date was jul 05,2022 that's why it showed the negative value and i added a new date jul 05,2023.
- In SubscriptionForm.js validate function after trim it is missing the property match () to match the regex pattern so it can validate the email.
- In hitToast.js I change the parameter order const hitToast = (message, variant) because when we use hitToast.js in SubscriptionForm.js we send the message value 1st then the variant thats bugs that failed to run toastify.
