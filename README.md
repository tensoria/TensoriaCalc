# TensoriaCalc
This page hosts the Mathematica package TensoriaCalc, which tackles concrete (semi-)Riemannian tensor calculus problems encountered in general relativity, cosmology, and field theory. Given a metric and the relevant coordinates, it automatically computes the relevant Christoffel symbols, Riemann curvature tensor, Ricci tensor and scalar, etc. Arbitrary space(time) tensors may be readily defined. Operations such as coordinate transformations, covariant derivatives, Lie derivatives, Hodge duals, etc. can be performed with TensoriaCalc's suite of in-built functions.

One key feature of TensoriaCalc is its smooth consistency with the Wolfram Language itself. Provided one is already familiar with the latter, this leads to its ease of use. For example, a geometry is defined by entering the metric (or its inverse) by simply feeding the function Metric a List of coordinates used, and either the usual quadratic form of coordinate differentials (or, partial derivatives) or a square matrix representing the (inverse) metric components themselves. There is no overhead spent in "declaring" space(time) indices. Multiple geometries can be defined without conflict.

During the 2010's, TensoriaCalc was first developed by Yi-Zen Chu as a computational tool for his research. In the first half of the 2020's, Wei-Hao Chen -- for his Master's thesis project -- joined the effort and extended its functionality considerably. During this time, Vaidehi Varma worked with both of us to carefully document the code and write its manual.

Please do feel free to use and/or modify this code, but only for the purposes of education or scientific research. If you do so, please cite the URLs of this GitHub webpage and Yi-Zen Chu's TensoriaCalc page (http://www.stargazing.net/yizen/Tensoria.html) in your publication(s). 

Comments, suggestions, bug reports, etc. are most welcomed too.

# What to download?
Mathematica packages are .m files. Hence, to run TensoriaCalc, simply download the TensoriaCalc.m file to the desired directory; and load it into your Mathematica session. 

On the other hand, the TensoriaCalc.nb file offers a more reader-friendly form of the code. To convert it into a .m file; first download it to the desired directory; Open it in Mathematica; then Save the file. This will create a TensoriaCalc.m file which can be loaded directly from any Mathematica session.

To get started in TensoriaCalc, consider working through TensoriaCalc_UserGuide.nb. It studies multi-variable calculus and various fundamental physics problems involving flat and curved space(time)s -- with a heavy emphasis on symmetry principles -- using TensoriaCalc's computational tools. This provides a hands-on introduction to the main features of TensoriaCalc.

The TensoriaCalc manual shall appear soon.
