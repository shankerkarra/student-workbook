# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
The ways to bind the data is using v-bind and v-model.

one-way: we can use one-way binding variable using {{ variable }} and also we can use v-bind( v-bind:attribute or :class="container") to bind variable inside an HTML element.

two-way binding: 
v-model is two-ways data binding, which allows binding DOM and data property, any change in one update the other, so data flows both ways.
(input v-model =""...)
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application

```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
SPA allows to render required components data without rendering  fast and responive the whole site. SPA allows to cache local data. SPA allows user experience in linear.

```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
Called when component is mounted to DOM for rendering the data

```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```

v-model allows two-way binding between data and views. One of the usage is to allow to add (using input fields) / display (other controls) without much impacting for browser refresh.

```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
The v:on executes function of a specific event like click, hover, mouseenter.

```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```

The Vue attributeslike v-if, v-else v-else-if for conditional render block of code based on the condition.

```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```

The purpose of the key attribute when using v-for is to track each node identity, for reuse & patch existing nodes for reordering or recreating.

```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```

The 'slot' elements is a placeholder inside a component. This element is used for development of widgets, or for reusability of the code.


```