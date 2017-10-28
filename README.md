# Go Tensorflow

root@ardeshir]:~/gosrc/github.com/ardeshir/gotf/api

0> curl localhost:9001/recognize -F 'image=@./cat.jpg'

{"filename":"cat.jpg","labels":[{"label":"Persian cat","probability":0.7091575},{"label":"Siamese cat","probability":0.12169986},{"label":"tabby","probability":0.084206946},{"label":"Egyptian cat","probability":0.04728738},{"label":"tiger cat","probability":0.02550238}]}
