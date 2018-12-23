# Time-Series-Analysis
Time series analysis using LSTM

### LSTM
  The Long Short-Term Memory network, or LSTM network, is a recurrent neural network that is trained using Backpropagation Through Time and overcomes the vanishing gradient problem.
  
  As such, it can be used to create large recurrent networks that in turn can be used to address difficult sequence problems in machine learning and achieve state-of-the-art results.
 
  Instead of neurons, LSTM networks have memory blocks that are connected through layers.A block has components that make it smarter than a classical neuron and a memory for recent sequences. A block contains gates that manage the block’s state and output. A block operates upon an input sequence and each gate within a block uses the sigmoid activation units to control whether they are triggered or not, making the change of state and addition of information flowing through the block conditional.
  
  There are three types of gates within a unit:
  
      -  Forget Gate: conditionally decides what information to throw away from the block.
      
      -  Input Gate: conditionally decides which values from the input to update the memory state.
      
      -  Output Gate: conditionally decides what to output based on input and the memory of the block.
     
