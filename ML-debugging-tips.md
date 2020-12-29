## Once you have "written" a model, steps to systematically debug:
1. **Get it running**: A lot of bugs might get addressed when trying to get things running
2. **verify tensor shapes**: Verify tensor shapes at different intermediate places
3. **check initialization**: If the model is blowing up/ not training properly, initialization could be the issue. 
4. **try setting the regularization very high/low**: Verify if the behavior of the model is as expected when the regularization is turned very high
5. **try keeping the model training for longer**: The loss drop should be gradual after the first epoch
6. **Monitor curves on TensorBoard**: babysit the models for the first few epochs, to check if things are happening the way you want them to
7. 
