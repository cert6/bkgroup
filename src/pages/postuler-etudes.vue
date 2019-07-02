<template>
<div>
    <div class="uk-height-medium uk-background-cover uk-position-relative" data-src="/img/school.jpeg" uk-img>

    <div class="uk-position-cover uk-overlay uk-overlay-primary">
<div class="uk-position-center">
    <br>
   <h1 class="font-weight-light"> 
       Etudier en chine , avec SICAS
       
   </h1>
</div>
    </div>
    </div>
    <div class="align-left main container ui segment basic">
<h1 class="uk-h2">
   Pièce à fournir
</h1>

<p>
    
</p>

    <h3>Faire une démande</h3>
    <span>Envoyez-nous votre requête via le formulaire en ligne ci-contre et nous vous répondrons sous 2 jours ouvrables.</span>
<br><br>
<div class="ui  inline field input">
<p><Input size="large" style="width: 333px" placeholder="Nom complet"/>&nbsp;
<Input size="large" style="width: 333px" placeholder="Adresse E-mail"/>
</p>
</div>
<br>
<div>
    <br>
    <p>
    <b>Votre message (Incluant votre parcours scolaire et votre demande )</b>

</p>
<p>
    <Input type="textarea" :autosize="{minRows: 4,maxRows: 9}" placeholder=""></Input>
</p>
<p>
    <v-btn dark color="red">
        <v-icon>send</v-icon> &nbsp;
        J'envoi ma demande
    </v-btn>
<h1 class="uk-h3">
    
    <span>les universités offrant des bourses d'études aux étudiants étrangers.</span>
    <br>
    <v-btn @click="$router.push('liste-university')" color="red" flat="">
        <v-icon>link</v-icon>&nbsp;
        Consulter la liste</v-btn>
</h1>
    
</p>

<div class="ui divider horizontal">Contacter nous</div>
<p>
    <i class="ui icon phone"></i> Téléphone : 71 69 25 38
</p>
<p>
    <i class="ui icon at"></i>Adresse E-mail : direction.generale@bkgroup-ci.org
</p>
</div>
<h1>&nbsp;</h1>

    </div>
</div>
</template>


<script>
export default {
    layout:"header"
}
</script>