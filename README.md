# What is object oriented programming?

![cut out cookies](cookies.jpg)
picture based on [photo from azerbaijan_stockers on freepik.com](https://de.freepik.com/fotos-kostenlos/prozess-der-behandlung-von-lebkuchenmannplaetzchen-benutzen-roten-lebkuchenmann-formausschnitt-lebkuchenteig-auf-backpapier-um-bunte-ausstechformen-auf-weissem-holztisch-ansicht-von-oben_5433582.htm)

This example repository shows the differences between plain imperative, object based and object oriented programming.

First of all: object oriented programming is not necessary to implement appropriate programms. It only makes the source code better readable and eases implementation for programmers.

Most examples about object orienten programming are really, because they only show the abstraction "object oriented" but do not show the "programming" part. This example shows the impementation of a car park display, which counts arriving and leaving cars:

## plain imperative programming

[Jupyter Notebook](oopno.ipynb)

This is the straight forward way. State variables and functions directly changing the values of these variables are written down without any idea of abstraction. This looks easy but is bad, if you want to doublicate the car park display to handle two different car parks.

## object based programming

[Jupyter Notebook](oopob.ipynb)

If we have two or more individual car parks, each one has its individual utilization independed from the other one. Also the capactity may differ. But the the concept, that cars can arrive or leave the car parks are identical for all car parks.

The idea is: Each car park should have a set of state variables ``totalSpaces``and ``usedSpaces`` used by the method functions being identical for all car parks.

## object oriented programming

[Jupyter Notebook](oopoo.ipynb)

While object based programming solves our problem, object oriented programming is a service the programming language offers to make the implementation more comfortable. Instantiation and initialisation are combined in one statement. Implicit destruction is supported. Also the association of member functions to the corresponding classes is handled by having the class as some kind of namespace and datatype in one. Class inheritance is supported.

*[Books about opject oriented programming on Amazon](https://amzn.to/3fEgqit)

*) Affiliate-Link - If you buy something on Amazon after clicking this Link, I get a sales commision from Amazon. You won't pay more.

# Impressum

https://entroserv.de/de/impressum
