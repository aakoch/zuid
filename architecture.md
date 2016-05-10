# Architecture

## MVC

Data Store -> Controller -> View

### Model
Any type of data store from flat files to a database (Firebase?)

### Controller
I was thinking Elm at first

### View
SVG by way of Elm's abstraction?

## Controller (in more detail)
1. Retrieves information from data store
1. Puts into data layers that are buffered
1. Receives input from device to manipulate