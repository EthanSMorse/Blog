# Titanic Analysis

On the day of April 15th, 1912, tragedy struck as the world famous "Titanic" sunk while on its maiden voyage. It hit an iceberg somewhere in the North Atlantic Ocean, and quickly sunk to the bottom of the sea.

And while this was, indeed a tragedy, It would also serve as an example for the future to come, helping us advance and ensure that nothing like that ever happened again

This is where the data that I was told to work with comes in. We were provided a data set, with which many questions could be both asked and answered. The graph below is accurate data from the sinking of the Titanic.

<br>

<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>PassengerId</th>
      <th>Survived</th>
      <th>Pclass</th>
      <th>Name</th>
      <th>Sex</th>
      <th>Age</th>
      <th>SibSp</th>
      <th>Parch</th>
      <th>Ticket</th>
      <th>Fare</th>
      <th>Cabin</th>
      <th>Embarked</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>0</td>
      <td>3</td>
      <td>Braund, Mr. Owen Harris</td>
      <td>male</td>
      <td>22.0</td>
      <td>1</td>
      <td>0</td>
      <td>A/5 21171</td>
      <td>7.2500</td>
      <td>NaN</td>
      <td>S</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>1</td>
      <td>1</td>
      <td>Cumings, Mrs. John Bradley (Florence Briggs Th...</td>
      <td>female</td>
      <td>38.0</td>
      <td>1</td>
      <td>0</td>
      <td>PC 17599</td>
      <td>71.2833</td>
      <td>C85</td>
      <td>C</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>1</td>
      <td>3</td>
      <td>Heikkinen, Miss. Laina</td>
      <td>female</td>
      <td>26.0</td>
      <td>0</td>
      <td>0</td>
      <td>STON/O2. 3101282</td>
      <td>7.9250</td>
      <td>NaN</td>
      <td>S</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>1</td>
      <td>1</td>
      <td>Futrelle, Mrs. Jacques Heath (Lily May Peel)</td>
      <td>female</td>
      <td>35.0</td>
      <td>1</td>
      <td>0</td>
      <td>113803</td>
      <td>53.1000</td>
      <td>C123</td>
      <td>S</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>0</td>
      <td>3</td>
      <td>Allen, Mr. William Henry</td>
      <td>male</td>
      <td>35.0</td>
      <td>0</td>
      <td>0</td>
      <td>373450</td>
      <td>8.0500</td>
      <td>NaN</td>
      <td>S</td>
    </tr>
  </tbody>
</table>
</div>

<br>

Using this data, I set out to answer three questions that I myself came up with. The following graphs are the result!

<br>

## Titanic Analysis: Question One


### How many people died/survived from each class?

<br>

The first information I wanted to know was the amount of deaths in each class, to see if the higher classes were more protected and valued than the lower classes.

<br>

![Graph for question 1: Number of people who died/survived in each class.](/assets/output.png)

<br>

And, based off of the graph, it would seem that those who paid for first class were significantly safer than those who didnt, with about 60 people dying. At the same time, those who got third class tickets were most definitely less protected if the vessel were to sink, with about 270 people dying.

This could be attributed to the fact that higher class rooms were on the higher floors to the boat, and therefore quicker to actually get off of the boat. It is even possible that those in third class had no time to react, as their rooms may have flooded instantaneously, killing them just as quickly.

<br>

## Titanic Analysis: Question Two


### How much did passengers pay for each class, on average?

<br>

Next, I wanted to see how much, on average, each class cost. If there is a great disparity between each class, then that would explain why higher classes would be more protected/valued.

<br>

![Graph for question 2: Average amount of money paid for each class.](/assets/output2.png)

<br>

And, looking above, we get a straightforward answer to this question. As can be seen, those who paid for first class had to pay significantly more for their tickets, about $60 more than both second and third class.

This could be another explanation as to why those in first class had significantly less deaths than those in the other two classes. They had paid more, so they were given more benefits, apparently including that of being less likely to die if the ship sinks.

<br>

## Titanic Analysis: Question Three


### How much did passengers pay for each class, on average?

<br>

Lastly, I wanted to check the overall average amount paid by those who died vs those who survived. This was just to solidify the idea that those who paid more were more likely to survive.

<br>

![Graph for question 3: ](/assets/output3.png)

<br>

And, as the graph shows, this still rings true. The amount paid by survivors is more than double than that of those who died. This, while showing the simple fact that money buys benefits, also shows how different the world was back then.

People nowadays would be absolutely outraged that those who paid less were more likely to die, most likely saying that it was unfair or built against people with less money. It just goes to show how different things become over time.

<br>

## Conclusion

<br>

To conclude, the data mostly shows how, at least back in the 1900's, money could be the difference between life and death.

You can review the code that was used to make the graphs here: https://github.com/EthanSMorse/Unit-2-Data-Science/blob/main/titanic_questions.ipynb