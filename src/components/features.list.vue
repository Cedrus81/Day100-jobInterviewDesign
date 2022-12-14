<template>
    <div class="feature-list-container">
        <ul class="feature-list flex justify-center">
            <li class="feature-list-item flex column align-center" v-for="feature in features">
                <img src="../assets/icons/icon-access-anywhere.svg" alt="123">
                <h2>{{feature.title}}</h2>
                <p>{{feature.desc}}</p>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    data(){
        return{
            features :[
            {
                imgSrc: '../assets/icons/icon-access-anywhere.svg',
                title: 'Access your files, anywhere',
                desc: 'The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.',
            },
            {
                imgSrc: '../assets/icons/icon-security.svg',
                title: 'Security you can trust',
                desc: '2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.',
            },
            {
                imgSrc: '../assets/icons/icon-collaboration.svg',
                title: 'Real-time collaboration',
                desc: 'Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.'
            },
            {
                imgSrc: '../assets/icons/icon-any-file.svg',
                title: 'Store any type of file',
                desc: `Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.`,
            },
            ]
        }
    }
}
</script>