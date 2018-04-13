Computing Resource
================================================================================

Daligner
--------------------------------------------------------------------------------

We suggest 16 G memory(daligner_mem) and 8 cpu(daligner_nproc) for each daligner tasks.

Small tasks
--------------------------------------------------------------------------------

For small tasks, which requires small memory, such as **LAq**, **LAstitch**, **LArepeat**, **LAgap**, **LAfilter**,
we suggest 2 G memory(small_mem) and 2 cpu(small_nproc) for each this kind of tasks.


Small tasks
--------------------------------------------------------------------------------

For big tasks, which requires huge memory, such as **TKmerge**, **OGbuild, **OGtour**, **tour2fasta**,
we suggest 60 G memory(small_mem) and 2 cpu(small_nproc) for each this kind of tasks.

You can easily change these settings in the config.cfg file.

Storage
--------------------------------------------------------------------------------

For a genome ~4.6Mb size with 50x PacBio reads, the storage for each folder is:

.. csv-table::
   :file: tables/storage.tsv
   :delim: tab
   :header-rows: 1
   :widths: 15, 10, 75

To save you storage, you can nohup the shell 'delete_marvel.sh' after you finished running run_marvel.

