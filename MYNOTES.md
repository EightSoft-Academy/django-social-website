## Django provides the following class-based views to deal with authentication.
All of them are located in _django.contrib.auth.views_:
Also go to settings and LOGIN_URL ...
- _LoginView_: Handles a login form and logs in a user
- _LogoutView_: Logs out a user
Django provides the following views to handle password changes:
- _PasswordChangeView_: Handles a form to change the user's password
- _PasswordChangeDoneView_: The success view that the user is redirected to after a successful password change
Django also includes the following views to enable users to reset their password:
- _PasswordResetView_: Allows users to reset their password. It generates
a one-time-use link with a token and sends it to a user's email account.
- _PasswordResetDoneView_: Tells users that an email—including a link to reset their password—has been sent to them.
- _PasswordResetConfirmView_: Allows users to set a new password.
- _PasswordResetCompleteView_: The success view that the user is redirected to after successfully resetting their password.

## Supported services for auth
https://python-social-auth.readthedocs.io/en/latest/backends/index.html#supported-backends

## django-extenions
``python manage.py runserver_plus --cert-file cert.crt``