# assignment-1

## Step 1. Get datadotworld package (assuming you have already installed anaconda)

Install datadotworld into your anaconda distribution by typing 

```
conda install -c conda-forge datadotworld-py 
```

Note: you should search for anaconda prompt in your machine and type the command in that prompt

Now finish the following excercises

## Step 2.  Introduction 

Hello and welcome to the intro to data.world tutorial! At data.world, we're building the most meaningful, collaborative, and abundant data resource in the world by breaking down the barriers between data and people. Join data.world to find interesting data and understand it at a glance, store and showcase your own data and data projects, as well as find and collaborate with others.

Open data is at the heart of data.world, and as such we want to make it as easy as possible to use data.world data in your environment of choice so you can do your work easier and solve real problems faster.

Which brings us to this tutorial where you’ll learn the different ways to connect to data.world using our Python SDK. The data.world Python SDK will help you to easily load data, explore metadata, query datasets and even push your work back to data.world for storage and sharing.

Learn more at https://data.world/integrations/python and let’s start with the basics of loading the datadotworld library and pulling in a dataset to kick things off….

### Instructions

* Import the datadotworld module as dw
* Use the load_dataset method to assign stephen-hoover/chicago-city-council-votes to a dataset variable.

in the following code. 

```
# Import the datadotworld module as dw
import ___ as ___

# Import the city council votes dataset
dataset = dw.___(___)
```

## Step 3: Reading Files

JSON is a common format to store and transfer hierarchical dictionary values in python.  Here is a JSON file. Copy it to a file called "test.json"
```JSON
{ "office": 
    {"medical": [
      { "room-number": 100,
        "use": "reception",
        "sq-ft": 50,
        "price": 75
      },
      { "room-number": 101,
        "use": "waiting",
        "sq-ft": 250,
        "price": 75
      },
      { "room-number": 102,
        "use": "examination",
        "sq-ft": 125,
        "price": 150
      },
      { "room-number": 103,
        "use": "examination",
        "sq-ft": 125,
        "price": 150
      },
      { "room-number": 104,
        "use": "office",
        "sq-ft": 150,
        "price": 100
      }
    ]},
    "parking": {
      "location": "premium",
      "style": "covered",
      "price": 750
    }
} 
 ```
 
* Now, Read the file into python and print the style of parking in office. Complete the following code
```
# import the json module
import ----

# open the file. Complete the filename
f=open(----)

# load JSON
--- = json.load(f)

#complete the next statement
print datastore["office"]["parking"]----
```





