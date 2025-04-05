<script>
    import Papers from "$lib/components/Papers.svelte";

    const paperLinks = [
        {
            name: "Urdu",
            link: "https://fbise.edu.pk/ModelPaper/2024New/urdu/Final_Assessment_Framework_Model_Question_Paper_Urdu_SSC-I.pdf#page=19",
        },
        {
            name: "English",
            link: "https://fbise.edu.pk/ModelPaper/2024New/english/Final_Assessment_Framework_Model_Question_Paper_English_SSC-I.pdf#page=30",
        },
        {
            name: "Islamiyat",
            link: "https://fbise.edu.pk/ModelPaper/2024New/islamiyat/Islamiyat%20Model%20Paper%20SSC-I%20(SNC%202022)%20Final.pdf",
        },
        {
            name: "Pakistan Studies",
            link: "https://fbise.edu.pk/ModelPaper/2024New/pst/Final_Assessment_Framework_Model_Question_Paper_PakistanStudies_SSC-I.pdf#page=15",
        },
        {
            name: "Chemistry",
            link: "https://fbise.edu.pk/ModelPaper/2024New/chemistry/Final_Assessment_Framework_Model_Question_Paper_Chemistry_SSC-I%20Latest.pdf#page=30",
        },
        {
            name: "Biology",
            link: "https://fbise.edu.pk/ModelPaper/2024New/bio/Final_Assessment_Framework_Model_Question_Paper_Biology_SSC-I.pdf#page=21",
        },
        {
            name: "Physics",
            link: "https://fbise.edu.pk/ModelPaper/2024New/physics/Final_Assessment_Framework_Model_Question_Paper_Physics_SSC-I.pdf#page=28",
        },
        {
            name: "Computer",
            link: "https://fbise.edu.pk/ModelPaper/2024New/computer/Final_Assessment_Framework_Model_Question_Paper_ComputerScience_SSC-I.pdf#page=25",
        },
        {
            name: "Mathematics",
            link: "https://fbise.edu.pk/ModelPaper/2024New/maths/Final_Assessment_Framework_Model_Question_Paper_Mathematics_SSC-I.pdf#page=17",
        },
    ];
</script>

<Papers grade="9" {paperLinks} />
