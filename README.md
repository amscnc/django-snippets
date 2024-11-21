# Django Snippets for Visual Studio Code

This extension provides a collection of commonly used Django snippets for Visual Studio Code, aimed at making Django app development quicker and easier. With these snippets, you can easily generate boilerplate code for views, models, imports, forms, authentication, and more, helping you streamline your workflow.

This project is open-source, and contributions are welcome! You can find the repository on [GitHub](https://github.com/amscnc/django-snippets).

## Features

### 1. **Views Snippets**
- `view:function`: Generates a basic function-based view.
- `view:class`: Generates a class-based view with common views like `ListView`, `DetailView`, and `CreateView`.
- [Coming Soon] `view:api`: Generates an API view using `APIView` from Django Rest Framework.
- [Coming Soon] `view:render`: Generates a `render` function for returning HTML responses.

### 2. **Model Snippets**
- `model`: Generates a basic Django model.
- `charfield`: Generates a `CharField` for Django models.
- `textfield`: Generates a `TextField` for Django models.
- `datefield`: Generates a `DateField` for Django models.
- `floatfield`: Generates a `FloatField` for Django models.
- `integerfield`: Generates an `IntegerField` for Django models.
- `booleanfield`: Generates a `BooleanField` for Django models.
- `date-time`: Generates a `DateTimeField` for Django models.
- `decimal`: Generates a `DecimalField` for Django models.
- `slugfield`: Generates a `SlugField` for Django models.

<!-- ### 3. **Forms & Validation Snippets**
- `form`: Generates a form class with fields.
- `model-form`: Generates a form based on a model using `ModelForm`.
- `form-field`: Adds a form field like `CharField`, `IntegerField`, etc. -->

### 3. **Common Django Imports**
- `httpresponse`: Import `HttpResponse` from `django.http`.
- `jsonresponse`: Import `JsonResponse` from `django.http`.
- `user`: Import `User` from `django.contrib.auth.models`.
- `models`: Import `models` from `django.db`.
- `admin`: Import `admin` from `django.contrib`.
- `gettextlazy`: Import `gettext_lazy` for translation.
- `views`: Import `views` from `django.shortcuts`.
- `redirect`: Import `redirect` from `django.shortcuts`.

<!-- ### 5. **Authentication Snippets**
- `login-required`: Adds a `login_required` decorator to a view function.
- `user-authentication`: Generates a user authentication check. -->

<!-- ### 6. **URL Snippets**
- `url-path`: Import `path` from `django.urls`.
- `url-reverse`: Import `reverse` from `django.urls`. -->

<!-- ### 7. **Miscellaneous Snippets**
- `admin-register`: Registers a model with the Django admin interface. -->

<!-- ## Installation

1. Open Visual Studio Code.
2. Go to the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
3. Search for "Django Snippets" and click Install. -->

Alternatively, you can install it manually from the VSIX file.

## Usage

Once installed, you can type the snippet prefix in your Django project files (e.g., `view-function`) and press `Tab` to expand the snippet. Below are some examples of how to use the snippets.

<!-- ### Example 1: Function View
Type `view:function` and press `Tab` to expand it into a basic function-based view:

```python

def my_view(request):
    return HttpResponse("Hello, World!") -->
