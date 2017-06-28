//RESTful routes


name url verb desc

for campplace
INDEX /campingplace          GET                             Display  list of all campplaces

NEW   /campingplace/newcamp  GET                             Show form to create new campplace

SHOW /campingplace/:id       GET                             Shows info about the campplace particularly

CREATE /campingplace         POST                            Add new campplace to my list


for comment
// we need nested routes

NEW  /campingplace/:id/comment/newcomment GET                 show form to create new comment

CREATE /campingplace/:id/comment          POST                Add new comment to particular campplace
