# ibm-omnibus-aggregator-sample
Project to hold: PROCESS AGENT, PRIMARY AGG, BACKUP AGG, BIREC GATEWAY


DEPLOY RAPIDO:

1-) EXPORTS
  export OMNIHOME=/monitoracao/IBM/tivoli/netcool/omnibus
  export NCHOME=/monitoracao/IBM/tivoli/netcool
  export PATH=$PATH:$OMNIHOME/bin:$NCHOME/bin

2-) AGGREGADORES
  nco_dbinit -server PRD_AGG_P
  nco_dbinit -server PRD_AGG_B
  
  
3-) Crie o PA basicão mesmo
 
4-) GATEWAY extensions bi-direc
   https://www.ibm.com/support/knowledgecenter/en/SSSHTQ_8.1.0/com.ibm.netcool_OMNIbus.doc_8.1.0/omnibus/wip/install/task/omn_esf_configuringbidiraggregationgtwy.html
   

5-) Ajuste o $NCHOME/etc/omni.dat
  Comando: nco_igen
  
  

  
