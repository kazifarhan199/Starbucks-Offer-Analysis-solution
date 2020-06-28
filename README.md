
![GitHub](https://img.shields.io/github/license/kazifarhanuddin/Starbucks-Offer-Analysis-solution)

![GitHub repo size](https://img.shields.io/github/repo-size/kazifarhanuddin/Starbucks-Offer-Analysis-solution)

# Starbucks-Offer-Analysis-solution

In this post we are going to look into Starbucks Offers Data, answer some interesting questions and then create a model that can predict weather a user will actually complete an offer or not.

## What is success

offer received -> offer viewed

offer received -> offer viewed -> offer completed

offer received -> offer completed

offer received 


Among all above conditions onlly the 2nd is success, because this is what we want the user to do, So lets create a new column for success

And the 3rd one is complete failure as we never want that to happen

### Objectives

1. Explore the data 
2. Answer some questions
3. Create a model that can predict success of an offer

#### Lest start off by looking at some questions

- Does the offer it self affect how customers interact with it
- Does type of offer determine how customers interact with it
- Does gender play a role in how customer react to offers
- Does income of the customer affect how they respond to offers 
- Can we create a model which can predict how a customers will react to an offer

## Dependency

1. pandas
1. sklearn
1. numpy
1. matplotlib

## Run Instructions:

1. Open jupyter notebook/lab the open the terminal 

2. Install dependencies

    `pip install -r requirements.txt`

3. To to the analysis file in jupyter notebook/lab and open it

## File structure 

```
├── README.md - a markdown file about this repo
├── data - a directory containing data
│   ├── portfolio.json - the file containing offer ids and meta data about each offer (duration, type, etc.)
│   ├── portfolio.json - the file containing demographic data for each customer
│   ├── portfolio.json - the file containing records for transactions, offers received, offers viewed, and offers completed
├── Starbucks-Offer-Analysis-solution.ipynb - file containg analysis
├── requirements.txt - File containing all dependencies
├── LICENSE - File containing license details
```

### Conclusion

- Does the offer it self affect how customers interact with it
    The answer is yes off cause the offer affect how people interact within
- Does type of offer determine how customers interact with it
    It dose to some extend but when it comes to discounts vs gobo, its not big of a deal
- Does gender play a role in how customer react to offers
    It does as we see all genders seem to have different reaction to offers as we saw women seem to have higher chance of buying something without looking at the offer, also they have the owes rejection rate when they see an offer, so may be the key is to send them offers with higher difficulty, where as men seem not to check the offer that much, so may be we can try to get more channels to reach them
- Does income of the customer affect how they respond to offers
    It does actual 75,000–102,000 seems to be the sweet spot, and from 102,000–111,000 seem to filled with people who complete offers even tho they never saw it
- Can we create a model which can predict how a customers will react to an offer
    Yes we can even tho the model, created over here does not  have the best score we can improve it, and it could be quite useful

## License

This project uses the MIT License
