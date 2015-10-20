---
layout: post
title: Demystify Angular Controller $scope vs. this
commentIssueId: 2
---

There are two main patterns we can use to construct controller functions in Angular.  The classic way is to use ```$scope``` to link controllers to views as such:

```
// View: <div ng-controller='LabController'></div>
app.controller('LabController', function ($scope) {
  $scope.labEquipment = {
    labEquipmentProperty: 'Some value'
  };
});
```

Since Angular version 1.2.0, we could use the ```this``` and ```Controller as``` syntax:

```
// View: <div ng-controller='LabController as lab'></div>
app.controller('LabController', function () {
  this.labEquipment = {
    labEquipmentProperty: 'Some value'
  };
});
```

These two paradigms are generally interchangeable.

##### Resources
1. <a href="http://toddmotto.com/digging-into-angulars-controller-as-syntax/" target="_blank">Digging into Angular's "Controller as" syntax</a> by Todd Motto
2. <a href="http://www.johnpapa.net/do-you-like-your-angular-controllers-with-or-without-sugar/" target="_blank">Do You Like Your Angular Controllers with or without Sugar?</a> by John Papa
