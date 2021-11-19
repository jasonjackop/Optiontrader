# Opitiontrader
#Essentially what I'm trying to do is constantly quote options that have large spreads, then immediatly triple greek neutralise by using matrices to hedge with other options,
#and using the underlying asset to hedge any leftover delta.
# the problem arises that i should only hedge with options if the volume im required to trade in order to hedge is relatively low as the markets for the options
# are illiquid. I will constantly need to check the greeks of these options and constantly compute matrix calculations to find what trades i need to make in order 
# to neutralise my delta,gamma,vega.
