<script>
    import Papers from "$lib/components/Papers.svelte";

    const paperLinks = [
        {
            name: "Urdu",
            link: "https://fbise.edu.pk/ModelPaper/2024New/urdu/Final%20HSSC-II%20Model%20Paper%20Urdu.pdf#page=4",
        },
        {
            name: "English",
            link: "https://fbise.edu.pk/ModelPaper/2024New/english/Final_English%20HSSC-II_merged.pdf#page=13",
        },
        {
            name: "Pakistan Studies",
            link: "https://fbise.edu.pk/ModelPaper/2024New/pst/Final%20HSSC-II%20Pakistan%20Studies%20Model%20Paper.pdf",
        },
        {
            name: "Chemistry",
            link: "https://fbise.edu.pk/ModelPaper/2024New/chemistry/Final%20HSSC-II%20Chemistry%20Model%20paper%20Merged.pdf",
        },
        {
            name: "Biology",
            link: "https://fbise.edu.pk/ModelPaper/2024New/bio/Final%20HSSC-II%20Biology%20Model%20paper.pdf",
        },
        {
            name: "Physics",
            link: "https://fbise.edu.pk/ModelPaper/2024New/physics/Final%20Model%20paper%20Physics%20HSSC-II%20revised.pdf",
        },
        {
            name: "Computer",
            link: "https://fbise.edu.pk/ModelPaper/2024New/computer/Final%20HSSC-II%20Model%20Paper%20Computer%20Science.pdf",
        },
        {
            name: "Mathematics",
            link: "https://fbise.edu.pk/ModelPaper/2024New/maths/Notification%20-%20Maths%20Model%20Question%20Paper%20HSSC-II%20(2006).pdf#page=2",
        },
        {
            name: "Chemistry",
            link: "https://fbise.edu.pk/ModelPaper/2025/Practical%20Based%20Assessment/Final%20Model%20Quesiton%20Paper%20PBA%20Chemistry%20HSSC-II.pdf#page=3",
            practical: true,
        },
        {
            name: "Biology",
            link: "https://fbise.edu.pk/ModelPaper/2025/Practical%20Based%20Assessment/Final%20Model%20Quesiton%20Paper%20PBA%20Biology%20HSSC-II.pdf#page=3",
            practical: true,
        },
        {
            name: "Physics",
            link: "https://fbise.edu.pk/ModelPaper/2025/Practical%20Based%20Assessment/Final%20Model%20Quesiton%20Paper%20PBA%20%20Physics%20HSSC-II.pdf#page=3",
            practical: true,
        },
        {
            name: "Computer",
            link: "https://fbise.edu.pk/ModelPaper/2025/Practical%20Based%20Assessment/Final%20Model%20Quesiton%20Paper%20PBA%20%20Computer%20Science%20HSSC-II.pdf#page=3",
            practical: true,
        },
    ];
</script>

<Papers grade="12" {paperLinks} />
