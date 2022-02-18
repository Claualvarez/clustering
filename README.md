# Useful paths 

Path to clans  
`/usr/local/bin/clans/clans.jar`

Path to input files  
`/home/blastdb/alignments/mitoRibosome`

# Prepare to use Linux graphical applications remotely

## Instructions for Windows users

[Configure Putty & Xming](https://laptops.eng.uci.edu/engineering-software/using-linux/how-to-configure-putty-xming-on-your-laptop)
1. [Xming](https://laptops.eng.uci.edu/engineering-software/using-linux/how-to-configure-putty-xming-on-your-laptop#h.vz90u7d6s3fh)
2. [Putty](https://laptops.eng.uci.edu/engineering-software/using-linux/how-to-configure-putty-xming-on-your-laptop#h.zfa31svy3pm5)
> Note: follow the steps as indicated, but in the box under Saved Sessions type apollo2.chemistry.gatech.edu  
> Then click on the Save button to the right. 


## Instructions for Mac users

`brew install --cask xquartz`

[PuTTY SSH client for Mac OSX](https://www.ssh.com/academy/ssh/putty/mac)


Connect to the VPN, then open a termianl and connect to apollo2 using ssh -X, for example:  
`ssh -X name@apollo2.chemistry.gatech.edu`


# Clans tutorial

Clans user guide [here](http://ftp.tuebingen.mpg.de/pub/protevo/CLANS/CLANS_userguide.pdf).

## Verify that you can open clans
1. Connect to the VPN
2. Connect to apollo2
3. In a terminal (in apollo2) type:  
`java -jar /usr/local/bin/clans/clans.jar`

## Load a run file in clans
1. Make a working directory in apollo2, for example:  
`mkdir mitoProteins_claudia`  
`cd mitoProteins_claudia`

2. Copy the example file for the tutorial to your working directory  
`cp /home/blastdb/alignments/mitoRibosome/example .`

3. Open clans and load the example file  
`java -jar /usr/local/bin/clans/clans.jar -load example -cpu 16`

You should see something like this:  
![](https://github.com/Claualvarez/clustering/blob/main/images/clans_example.png)

4. Check the `show connections` box

5. Click the `slect/MOVE` button to change from moving to selecting mode.  
6. The button now should say `SELECT/move`

## Modify the P-value 

## Find clisters

## Edit groups
