<script>
    import Papers from "$lib/components/Papers.svelte";

    const paperLinks = [
        {
            name: "Urdu",
            link: "https://fbise.edu.pk/ModelPaper/2024New/urdu/Final_Assessment_Framework_Model_Question_Paper_Urdu_HSSC-I.pdf#page=19",
        },
        {
            name: "English",
            link: "https://fbise.edu.pk/ModelPaper/2024New/english/Final_Assessment_Framework_Model_Question_Paper_English_HSSC-I%20(2).pdf#page=31",
        },
        {
            name: "Islamiyat",
            link: "https://fbise.edu.pk/ModelPaper/2024New/islamiyat/Final_Assessment_Framework_Model_Question_Paper_Islamiyat_HSSC-I.pdf#page=11",
        },
        {
            name: "Chemistry",
            link: "https://fbise.edu.pk/ModelPaper/2024New/chemistry/Final_Assessment_Framework_Model_Question_Paper_Chemistry_HSSC-I.pdf#page=39",
        },
        {
            name: "Biology",
            link: "https://fbise.edu.pk/ModelPaper/2024New/bio/Final_Assessment_Framework_Model_Question_Paper_Biology_HSSC-I.pdf#page=40",
        },
        {
            name: "Physics",
            link: "https://fbise.edu.pk/ModelPaper/2024New/physics/Final_Assessment_Framework_Model_Question_Paper_Physics_HSSC-I.pdf#page=27",
        },
        {
            name: "Computer",
            link: "https://fbise.edu.pk/ModelPaper/2024New/computer/Final_Assessment_Framework_Model_Question_Paper_ComputetScience_HSSC-I.pdf#page=24",
        },
        {
            name: "Mathematics",
            link: "https://fbise.edu.pk/ModelPaper/2024New/maths/Final_Assessment_Framework_Model_Question_Paper_Mathematics_HSSC-I_.pdf#page=18",
        },
    ];
</script>

<Papers grade="11" {paperLinks} />
