Today I asked fastai... is a house a forest or a bird?
And I received an answer.

The house in question:

## My Question

    is_bird,_,probs = learn.predict(PILImage.create('house.jpg'))

    print(f"This is a: {is_bird}.")
    print(f"Probability it's a bird: {probs[0]:.4f}")
    print(f"Probability it's a forest: {probs[1]:.4f}")

    print(probs)
 
 ## ... And My Answer
    
    This is a: forest.
    Probability it's a bird: 0.1705
    Probability it's a forest: 0.8295
    
So there you have it... a house is a forest. 

But past jokes, these answer is consistent with expectations due to dense tree foliage in the background, but interesting to test the deep learning algorithm used. 
