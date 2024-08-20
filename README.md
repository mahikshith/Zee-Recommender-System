#  Zee Recommender System
 Building a recommender system based on movies, users , review database

#### **What is a Recommender System?**

A recommender engine, or a recommendation system is a subclass of information filtering system that seeks to predict the "rating" or "preference" a user would give to an item.

#### **Types of Recommender Systems -**

Recommender systems usually make use of either or both *Collaborative Filtering* and *Content-based Filtering* techniques.

#### **Collaborative Filtering**

Collaborative filtering is based on the assumption that people who agreed in the past will agree in the future, and that they will like similar kinds of items as they liked in the past. The system generates recommendations using only information about rating profiles for different users or items. By locating peer users/items with a rating history similar to the current user or item, they generate recommendations using this neighborhood.

#### **Content-based Filtering**

Content-based filtering methods are based on a description of the item and a profile of the user's preferences. These methods are best suited to situations where there is known data on an item (name, location, description, etc.), but not on the user. Content-based recommenders treat recommendation as a user-specific classification problem and learn a classifier for the user's likes and dislikes based on an item's features.

#### Comparing the results : 

<div>

</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>correlation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Liar Liar</th>
      <td>1.000000</td>
    </tr>
    <tr>
      <th>Mrs. Doubtfire</th>
      <td>0.499927</td>
    </tr>
    <tr>
      <th>Dumb &amp; Dumber</th>
      <td>0.459601</td>
    </tr>
    <tr>
      <th>Ace Ventura: Pet Detective</th>
      <td>0.458654</td>
    </tr>
    <tr>
      <th>Home Alone</th>
      <td>0.455967</td>
    </tr>
    <tr>
      <th>Wedding Singer, The</th>
      <td>0.429222</td>
    </tr>
    <tr>
      <th>Wayne's World</th>
      <td>0.424552</td>
    </tr>
    <tr>
      <th>Cable Guy, The</th>
      <td>0.420942</td>
    </tr>
    <tr>
      <th>Tommy Boy</th>
      <td>0.413143</td>
    </tr>
    <tr>
      <th>Austin Powers: International Man of Mystery</th>
      <td>0.411105</td>
    </tr>
  </tbody>
</table>
</div>

############################################################################### 

<div>

</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>cosine_Similarity</th>
    </tr>
    <tr>
      <th>title</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Liar Liar</th>
      <td>1.000000</td>
    </tr>
    <tr>
      <th>Mrs. Doubtfire</th>
      <td>0.557067</td>
    </tr>
    <tr>
      <th>Ace Ventura: Pet Detective</th>
      <td>0.516861</td>
    </tr>
    <tr>
      <th>Dumb &amp; Dumber</th>
      <td>0.512585</td>
    </tr>
    <tr>
      <th>Home Alone</th>
      <td>0.511204</td>
    </tr>
    <tr>
      <th>Wayne's World</th>
      <td>0.499368</td>
    </tr>
    <tr>
      <th>Wedding Singer, The</th>
      <td>0.497076</td>
    </tr>
    <tr>
      <th>Austin Powers: International Man of Mystery</th>
      <td>0.489473</td>
    </tr>
    <tr>
      <th>There's Something About Mary</th>
      <td>0.483263</td>
    </tr>
    <tr>
      <th>League of Their Own, A</th>
      <td>0.482074</td>
    </tr>
  </tbody>
</table>
</div>

################################################################# 

<div>

</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>knn_disatnce</th>
    </tr>
    <tr>
      <th>title</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Liar Liar</th>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>Mrs. Doubtfire</th>
      <td>0.442933</td>
    </tr>
    <tr>
      <th>Ace Ventura: Pet Detective</th>
      <td>0.483139</td>
    </tr>
    <tr>
      <th>Dumb &amp; Dumber</th>
      <td>0.487415</td>
    </tr>
    <tr>
      <th>Home Alone</th>
      <td>0.488796</td>
    </tr>
    <tr>
      <th>Wayne's World</th>
      <td>0.500632</td>
    </tr>
    <tr>
      <th>Wedding Singer, The</th>
      <td>0.502924</td>
    </tr>
    <tr>
      <th>Austin Powers: International Man of Mystery</th>
      <td>0.510527</td>
    </tr>
    <tr>
      <th>There's Something About Mary</th>
      <td>0.516737</td>
    </tr>
    <tr>
      <th>League of Their Own, A</th>
      <td>0.517926</td>
    </tr>
  </tbody>
</table>
</div>
