SLAM on Parkour Car
====================
Many years ago, I tried running a sparse SLAM algorithm clled `RSLAM <https://github.com/arpg/rslam>`_ on a Jetson TK1 computer which was at the time the main computer for my Parkour Car platform.

Eventhough, I was able to run RSLAM successfully but because of low update rate (4-5 estimates/sec) I decide to move on with Vicon feedback instead.
One can always optimize available sparse slam methods (like frame resizing, number of features, ... ) to get a higher update rate but since that was not focus of my research I didn't work on it further.

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/FY1miFaJiJ4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>