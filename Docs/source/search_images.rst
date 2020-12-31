**************************************************
Search Images
**************************************************
It searches the keyword passed in keyword on google in images.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: google.search_images(keyword="keyword")

   
   :param str keyword: Keyword which need to be search on google
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict