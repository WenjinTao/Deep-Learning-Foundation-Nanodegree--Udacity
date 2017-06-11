Note:

Here's the command to launch jupyter through floyd with gpu activated, using floyd hosted dataset.


`floyd run --mode jupyter --gpu --data data_id`

data_id is `R5KrjnANiKVhLWAkpXhNBe` in this project.

Use `floyd status` to check the experiment list.

To stop an experiment, use `floyd stop RUN_ID`.