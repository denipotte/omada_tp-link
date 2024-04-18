# UPDATE OMADA

    Transferir o arquivo de update para o seridor
        Via scp ou wget
        scp omada_v5.13.30.8_linux_x64_20240131200337_1709001433903.deb sti@143.107.199.8:


    https://143.107.199.8:8043/
    ssh sti@143.107.199.8
    Poi.....
    su -
        
        Parar o serviço do OMADA para poder atualizar  
        tpeap stop

        Instalar o pacote
        dpkg -i /home/sti/omada_v5.13.30.8_linux_x64_20240131200337_1709001433903.deb

        Iniciar o serviço
        tpeap start

        