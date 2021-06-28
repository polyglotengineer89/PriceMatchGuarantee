<h4>Description</h4><br>

Do you scan online retailers in search of the best deals? You're joined by the many savvy shoppers who don't like paying extra for the same product depending on where they shop. Retail companies use a variety of methods to assure customers that their products are the cheapest. Among them is product matching, which allows a company to offer products at rates that are competitive to the same product sold by another retailer. To perform these matches automatically requires a thorough machine learning approach, which is where your data science skills could help.

Two different images of similar wares may represent the same product or two completely different items. Retailers want to avoid misrepresentations and other issues that could come from conflating two dissimilar products. Currently, a combination of deep learning and traditional machine learning analyzes image and text information to compare similarity. But major differences in images, titles, and product descriptions prevent these methods from being entirely effective.

Shopee is the leading e-commerce platform in Southeast Asia and Taiwan. Customers appreciate its easy, secure, and fast online shopping experience tailored to their region. The company also provides strong payment and logistical support along with a 'Lowest Price Guaranteed' feature on thousands of Shopee's listed products.

In this competition, you’ll apply your machine learning skills to build a model that predicts which items are the same products.

The applications go far beyond Shopee or other retailers. Your contributions to product matching could support more accurate product categorization and uncover marketplace spam. Customers will benefit from more accurate listings of the same or similar products as they shop. Perhaps most importantly, this will aid you and your fellow shoppers in your hunt for the very best deals.

Submissions will be evaluated based on their mean F1 score. The mean is calculated in a sample-wise fashion, meaning that an F1 score is calculated for every predicted row, then averaged.

<h4>Submission File</h4><br>
You must create a space-delimited list of all posting_ids that match the posting in the posting_id column. Posts always self-match. Group sizes were capped at 50, so there is no benefit to predict more than 50 matches.

The file should have a header, be named submission.csv, and look like the following:

posting_id,matches
test_123,test_123
test_456,test_456 test_789
You should predict matches for every posting_id. For example, if you believe A matches B and C, A,A B C, you would also include B,B A C and C,C A B.

