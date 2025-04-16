# MARIO-GAME-By-use-of-java-
public class MCQScreen implements Screen {
    private final Game game;
    private final Question currentQuestion;

    public MCQScreen(Game game, Question question) {
        this.game = game;
        this.currentQuestion = question;
    }

    @Override
    public void show() {
        // Initialize UI elements to display the question and options
    }

    @Override
    public void render(float delta) {
        // Render the question and handle user input
    }

    // Other required methods: resize, pause, resume, hide, dispose
}
public class Question {
    private String questionText;
    private List<String> options;
    private int correctAnswerIndex;

    // Constructor, getters, and setters
}
public class QuestionLoader {
    public static List<Question> loadQuestions(String filePath) {
        // Use a JSON parsing library like Gson or Jackson to read questions from the file
    }
}
