#Phone
##About phone
For simple formatting of phone numbers, include InputPhoneNumber.
## Software Requirements
- React js
- Rails 5.0
- Bootstrap 3
##Use cases
- Simple example for formatting a phone number in input text
```
    <%=react_component('InputPhoneNumber',id:"phone", class_name:"form-control input-lg", dataformat: "+61 d dddd dddd", placeholder:"+61 9 9999 9999") %>
```
- Example for formatting a phone number in input text with a predefined number
```
    <%=react_component('InputPhoneNumber',id:"phone", class_name:"form-control input-lg", dataformat: "+61 d dddd dddd", placeholder:"+61 9 9999 9999"), value:"453265876" %>
```
