class Hala extends Developer
{
    public String $name = "Hala Abu Salim";
    public String $position = "Full-Stack Developer";

    public function knowledge()
    {
        return collect([
            "Laravel",
            "NuxtJs",
            "NestJs",
        ]);
    }

    public function media()
    {
        return collect([
            "linkedin" => "www.linkedin.com/in/hala-abusalim",
            "medium" => "https://medium.com/@hala.s.salim",
        ]);
    }
}
