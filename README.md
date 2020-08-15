This Readme will be better explained later, but for now we got:

This repository contains two .Net Core 3.1 projects:
  1. Basic Scaffold .NetCore 3.1 WebApi
  2. Console with authentication and a call to the WebApi

The authentication is based in Azure AD. First, the Console App gets the Token via AD and then makes a HTTP GET Request with Bearer Authentication to get the default data from de WebApi
