### property-based-testing

##Links

#Documents

 - http://fsharpforfunandprofit.com/posts/property-based-testing/
 - http://fsharpforfunandprofit.com/posts/property-based-testing-2/
 
 - https://tomphp.github.io/testing/2016/06/06/a-case-for-property-based-testing.html

 - http://hypothesis.works/articles/incremental-property-based-testing/
 
 - http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.93.5559&rep=rep1&type=pdf
 
 - https://truizlop.github.io/development/property-based-testing-introduction/
 
 #Videos : 
 - http://fsharpforfunandprofit.com/pbt/
 -  john hughes talk : https://www.youtube.com/watch?v=zi0rHwfiX1Q
 -  Article from Nat Pryce : http://natpryce.com/articles/000807.html
 - Romeu Moura video  : http://videos.ncrafts.io/video/170129851

##Library

 - python : http://hypothesis.works


Discussion on [slack](https://softwarecraftsmanship.slack.com/messages/propertybasedtesting/) : 

@franzi
I learned that PBT can be applied to all levels of testing, much like acceptance tests
and that the business in BDD often wants to give us properties, not examples, and the examples are just a verification that we understood correctly
we should note the properties that the business wants to give us and test them

I learned how Nat uses broad to narrow properties to baby step PBT and Property Test Driven Development
and how PBT can be applied as characterisation tests and documentation for legacy code, flushing out obscure exceptions in business rules 
then we can go to the business and ask if it’s a bug or a feature


I learned that PBT doesn’t prove your solution is right, but you can spot more problems by generating input that favours exceptional cases
