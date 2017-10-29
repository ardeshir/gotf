# Go Tensorflow

root@ardeshir]:~/gosrc/github.com/ardeshir/gotf/api

0> curl localhost:9001/recognize -F 'image=@./fruitbowl.jpg'

```javascript

{
    "filename": "fruitbowl.jpg",
    "labels": [{
        "label": "orange",
        "probability": 0.43016684
    }, {
        "label": "lemon",
        "probability": 0.20536041
    }, {
        "label": "Granny Smith",
        "probability": 0.108103454
    }, {
        "label": "bell pepper",
        "probability": 0.059770357
    }, {
        "label": "mortar",
        "probability": 0.046001446
    }]
}

```
