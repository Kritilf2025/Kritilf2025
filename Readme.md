/**
 * 🎯 TITLE: KRITI KUMARI - RESILIENCE IN CODE & MIND
 * 
 * 🔥 This Code Describes:
 * - Emotional resilience (via quantum simulation)
 * - Mental clarity (via math functions)
 * - Core Java skills (OOP, interfaces, enums)
 * - Aspirations in AI, Physics, and Meaningful Problem Solving
 */

import java.util.*;

interface QuantumState {
    double observeProbability();
    String getStateLabel();
}

class EmotionSuperposition implements QuantumState {
    private final String[] states = {"Collapsed", "Rebuilt"};
    private final double[] probabilities = {0.3, 0.7};
    private final int cachedIndex;

    public EmotionSuperposition() {
        Random rand = new Random();
        this.cachedIndex = rand.nextInt(states.length);
    }

    @Override
    public double observeProbability() {
        return probabilities[cachedIndex];
    }

    @Override
    public String getStateLabel() {
        return states[cachedIndex];
    }
}

class MathResilience {
    public static double exponentialRecovery(double trauma, double time) {
        return Math.exp(-trauma * time);
    }

    public static double probabilityOfHealing(double clarity, double emotionalMastery) {
        double product = clarity * emotionalMastery;
        return Math.min(1.0, product);
    }
}

class KritiKumari {
    private final String name = "Kriti Kumari";
    private final double cgpa = 9.15;
    private final String institution = "Galgotias University";
    private final List<String> passions = Arrays.asList("AI", "Java", "Python", "Physics", "Mental Health", "Problem Solving");
    private final EmotionSuperposition emotionalState = new EmotionSuperposition();

    public void describeJourney() {
        System.out.printf("""
                From emotional collapse to mental mastery:
                I am %s, currently pursuing MCA at %s.
                My journey wasn't linear — I went from excelling in ICSE with 93.4%% to facing toxicity and emotional collapse.
                Yet I qualified BIT Mesra for Physics without coaching during crisis — that shows resilience.
                I switched to CS not out of failure but maturity, reigniting my love for coding from Class 10.
                CGPA in MCA (Sem 1): %.2f
                Quantum Emotional State: %s
                Observed Healing Probability: %.2f
                Calculated Probability of Mental Clarity & Healing: %.2f
                Exponential Emotional Recovery (trauma=1.2, time=3): %.5f
                Core Passions: %s

                """, name, institution, cgpa,
                emotionalState.getStateLabel(),
                emotionalState.observeProbability(),
                MathResilience.probabilityOfHealing(0.98, 0.95),
                MathResilience.exponentialRecovery(1.2, 3),
                passions
        );
    }

    public void showCoreValues() {
        System.out.println("""
                Mental health is the root of genius and stability.
                Bugs are blessings — they sharpen logic.
                Curiosity is sacred. Kindness is power. Focus is clarity.
                """);
    }

    public void careerGoals() {
        System.out.println("""
                My Aspirations:
                1. Build AI-powered, physics-aware intelligent systems.
                2. Solve real-world problems with Core Java, data structures, algorithms, and networks.
                3. Craft software that not only works — but heals, empowers, and transforms lives.
                """);
    }

    public void gratitude() {
        System.out.println("""
                Falling sick was the turning point of my life.
                It forced me to face myself, to transform pain into power.
                It gifted me wisdom, emotional control, and intense mental clarity.
                """);
    }

    public void emotionalSensitivity() {
        System.out.println("""
                Whenever someone I deeply respect is hurt or disappointed by me,
                I feel a piercing pain in my stomach. It's real — not metaphorical.
                This pain stays until I feel they have forgiven me. My body can't fake integrity.
                """);
    }
}

public class KritiAboutMeJava {
    public static void main(String[] args) {
        KritiKumari kriti = new KritiKumari();

        System.out.println("==============================");
        System.out.println("💥✨  KRITI KUMARI - RESILIENCE IN CODE & MIND ✨💥");
        System.out.println("==============================\n");

        kriti.describeJourney();
        kriti.showCoreValues();
        kriti.careerGoals();
        kriti.gratitude();
        kriti.emotionalSensitivity();
    }
}
