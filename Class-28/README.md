# Class-28
## I’ve reviewed the following topic:

-  Django Forms

Django provides a Form class which is used to create HTML forms. It describes a form and how it works and appears.

It is similar to the ModelForm class that creates a form by using the Model, but it does not require the Model.

Each field of the form class map to the HTML form <input> element and each one is a class itself, it manages form data and performs validation while submitting the form.

Working with forms can be complicated! Developers need to write HTML for the form, validate and properly sanitize entered data on the server (and possibly also in the browser), repost the form with error messages to inform users of any invalid fields, handle the data when it has successfully been submitted, and finally respond to the user in some way to indicate success. Django Forms take a lot of the work out of all these steps, by providing a framework that lets you define forms and their fields programmatically, and then use these objects to both generate the form HTML code and handle much of the validation and user interaction.


Into the django template you need add submit button manually.

Template code:

<form method="post">
{% csrf_token %}

{{ form.as_p }}

<input type="submit" value="Submit" />
</form>