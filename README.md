# Grok_Fast_Tensorflow
The tensorflow implementation of Grok Fast

Only the EMA version has been implemented

Feel free to use my implementation for tensorflow's functional API.

Usage
Replace
model = tf.keras.Model(inputs=inputs, outputs=outputs)
with
model = Grok_Fast_EMA_Model(alpha=0.99, lamb=5, inputs=inputs, output=outputs)
