<img align="right" src="img/cphbusinessWhite.png" />  
#Angular week 2
Content: 
1. Custom filters
2. Custom services
3. Custom Directives
4. Security in the angular seed project

##Angular filters and Services
1. What is a service
2. Service vs. Factory vs. Provider vs. Value
3. Show ephemeral nature of controllers [here]()
4. Example with service
5. Example with factory


##Angular custom directives
1. Build-in directives e.g:
	1. ng-bind
	2. ng-repeat
	3. ng-model
2. Custom directives

###Template-expanding directive
A chunk of code that is repeated many times in your code. When you change it in one place, you have to change it in several others. This is a good opportunity to use a directive to simplify your template.

### Example
- Returning an object:
```
.directive('myCustomer', function() {
  return {
    templateUrl: function(elem, attr) {
      return 'customer-' + attr.type + '.html';
    }
  };
});
```
###Properties of the directive object
1. restrict
2. template
3. templateUrl
4. scope
5. link

###Normalization
- The normalization process is as follows:
   - Strip x- and data- from the front of the element/attributes.
   - Convert the :, -, or _-delimited name to camelCase.
   - For example, the following forms are all equivalent and match the ngBind directive:
```
	  <span ng-bind="name"></span> <br/>
	  <span ng:bind="name"></span> <br/>
	  <span ng_bind="name"></span> <br/>
	  <span data-ng-bind="name"></span> <br/>
	  <span x-ng-bind="name"></span> <br/>
```


##Token based security




### sub sub for individual slides ()
#### sub sub sub goes all the way to 6 hashes

![alt text](img/domtree.png) Most common tags are:

![alt text](img/element.png)

- bullet point
  - to spaces before makes it a sub bullet point (indent by 2 spaces for each sub level)

1. ordered list
  1. ordered sublist indent by 2 spaces
  
[This is a link](http://www.w3schools.com/cssref/tryit.asp?filename=trycss_sel_firstchild_more3)

javascript```
This in here will be interpreted as a code snippet. write javascript, css and others
```  

REMEMBER to add two spaces after a paragraph to ensure newlines