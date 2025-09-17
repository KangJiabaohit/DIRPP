# DIRPP

Resources for our EMNLP 2025 paper: Exploring Deductive and Inductive Reasoning Capabilities of Large Language Models in Procedural Planning

## Dataset Format

Each data entry in the dataset is a JSON object containing the following fields:

- `id`: A unique integer identifier for the data sample
- `abstract goal`: An abstract goal. It is the abstraction of a specific goal.
- `abstract script`: A procedural plan for achieving the abstract goal.
- `specific goal`: A specific goal. It is the concretization of an abstract goal.
- `specific script`: A procedural plan for achieving the specific goal.

### Example Data Entry

Here's an example data entry from the dataset:

{

  "id": 1,
  "abstract goal": "making a sundae",
  "abstract script": [

​	1. Gather all the ingredients: ice cream, toppings, and a bowl.

​	2.Choose your favorite flavor of ice cream.

​	3.Scoop the ice cream into the bowl.

​	4.Add your desired toppings, such as chocolate syrup, sprinkles, or nuts.

​	5.Optionally, add whipped cream on top.

​	6.Place a cherry on top if desired.

​	7.Grab a spoon and enjoy your sundae.]，

  "specific goal": "making a sundae with fruit",

  "specific script": [

​	1.Gather all the ingredients: ice cream, fruit (such as bananas, strawberries, or cherries), whipped cream, and any toppings (like nuts or chocolate syrup).

​	2.Choose a bowl or glass to serve the sundae.

​	3.Scoop the desired amount of ice cream into the bowl.

​	4.Slice the fruit into bite-sized pieces.

​	5.Arrange the sliced fruit on top of the ice cream.

​	6.Add whipped cream on top of the fruit.

​	7.Drizzle chocolate syrup or any other topping over the whipped cream.

​	8.Sprinkle nuts or other toppings if desired.

​	9.Serve immediately with a spoon.]

}





