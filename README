An Extension of studyforrest.org Dataset
****************************************

Multi-resolution 3T fMRI data on the representation of visual orientation
=========================================================================

This dataset consists of empirical 3T fMRI data recorded at three spatial
resolutions (1.4 mm, 2 mm, and 3 mm isotropic voxel size) for orientation
decoding in visual cortex — in order to test hypotheses on the strength and
spatial scale of orientation discriminating signals. This is an extension of
the studyforrest project. All seven participants previously volunteered for the
audio-only and the audio-visual Forrest Gump study.
Five of the seven participants also participated in a matching study using
identical protocols, but 7T data acquisition (with the same the three spatial
resolutions used here, plus a 0.8 mm acquisition). The dataset is compliant
with the BIDS data description standard (http://bids.neuroimaging.io).  A
detailed description can be found in:

  Sengupta, A., Speck, O., Yakupov, R., Kanowski, M., Tempelmann, C.,
  Pollmann, S. & Hanke, M. (2018) The effect of acquisition resolution on
  orientation decoding from V1: comparison of 3T and 7T. bioRxiv.

  https://doi.org/10.1101/305417

For more information about the project visit: http://studyforrest.org


How to obtain the data files
----------------------------

This repository contains metadata and information on the identity of all
included files. However, the actual content of the (sometime large) data
files is stored elsewhere.

Using DataLad (http://datalad.org)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Install this dataset:

    datalad install URL

Obtain any files (example all files, but individual files can be requested)

    datalad get .

Obtain dataset updated

    datalad update --merge


Using git/git-annex
~~~~~~~~~~~~~~~~~~~

To obtain any dataset component, git-annex_ is required in addition to Git_.

1. Clone this repository to the desired location.
2. Enter the directory with the local clone and run::

     git annex init

   Older versions of git-annex may require you to run the following
   command immediately afterwards::

     git annex enableremote mddatasrc

Now any desired dataset component can be obtained by using the ``git annex get``
command. To obtain the entire dataset content run::

     git annex get .

Keep data up-to-date
--------------------

If updates to this dataset are made in the future, update any local clone by
running::

     git pull

followed by::

     git annex get .

to fetch all new files.

.. _Git: http://www.git-scm.com

.. _git-annex: http://git-annex.branchable.com/
