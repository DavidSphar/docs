=============
MagnitudeAxis
=============

.. note:: This section is under construction. Please contribute!

.. image:: MagnitudeAxis.png

Example
-------

.. code:: csharp

    var model = new PlotModel { Title = "MagnitudeAxis" };
    model.Axes.Add(new LinearAxis { Position = AxisPosition.Bottom, Minimum = -20, Maximum = 80});
    model.Axes.Add(new LinearAxis { Position = AxisPosition.Left, Minimum = -10, Maximum = 10});
