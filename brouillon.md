    // style du header 
    header {
        background-image: url('./ressources/bg_maquette_figma.jpg');
        background-position: center;
        background-repeat: no-repeat;
        color: $color3;
        height: 500px;
    }

    i {
        size: 200%;
    }

    .testhead > h1 {
        position: sticky;

    }

    .testhead > form {
        position: sticky;
    }
    // style des bouton 
    button {
        border: unset;
        color: $color1;
        color:#FFFFFF;
    }
    
    // style des icons puzzle 
    i {
        color: $color1;
    }


    // style des input 
    input , textarea {
        background-color: #D9D9D9;
        border: unset;
        border-radius: 15px;

        // & placeholder = + l'attribut placeholder du selecteur précedent
        &::placeholder {
        color: #F8F9FA;

        }

    .article {  
        display: flex;
        flex-direction: row;
    }
    }
}