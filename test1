from django import forms
from djangular.forms.angular_model import NgModelFormMixin 

class RegisterForm(NgModelFormMixin, forms.Form):
	userName = forms.CharField()
	password = forms.CharField()
	confirm  = forms.CharField()
	email    = forms.EmailField()
	firstname = forms.CharField()
	lastname  = forms.CharField()
	hobby     = forms.CharField(required=False)
