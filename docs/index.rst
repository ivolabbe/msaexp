.. raw:: html

    <style media="screen" type="text/css">
      h1 {display:none;}
    </style>

*********
msaexp
*********

Tools for extracting JWST NIRSpec MSA spectra directly from the telescope exposures

Under heavy construction....

.. note::
    Please submit any questions/comments/problems you have through the `Issues <https://github.com/gbrammer/msaexp/issues>`_ interface.

~~~~~~~~~~~~~
Documentation
~~~~~~~~~~~~~

The overall procedure is demonstrated in two notebooks:

- `process-rxj2129.ipynb <https://github.com/gbrammer/msaexp/blob/main/docs/examples/process-rxj2129.ipynb>`_: Demo with prism data from JWST program `DD-2767 <https://www.stsci.edu/cgi-bin/get-proposal-info?id=2756&observatory=JWST>`_ (PI: Pat Kelly)
- `process-smacs0723.ipynb <https://github.com/gbrammer/msaexp/blob/main/docs/examples/process-smacs0723.ipynb>`_: Demo with medium resolution data from the JWST `ERO-2736 <https://www.stsci.edu/cgi-bin/get-proposal-info?id=2736&observatory=JWST>`_ program on the cluster SMACS-0723 (PI: Klaus Pontoppidon)

Try running the RXJ2129 demo notebook directly on GitHub in a Codespace: 
  1. Fork the repository from https://github.com/gbrammer/msaexp
  2. `<> Code` pulldown > `Codespaces` > `+` to start the codespace
  3. Wait for the initialization to complete
  4. Navigate to the `docs/examples/` directory in the codespace
  5. Open `process-rxj2129.ipynb` and run it
  6. Commit to your forked repository any changes to the notebook itself or files created that you want to save outside the codespace
  7. Profit!

.. toctree::
   :maxdepth: 2

   msaexp/install.rst

~~~     
API
~~~

.. toctree::
   :maxdepth: 2

   msaexp/api.rst