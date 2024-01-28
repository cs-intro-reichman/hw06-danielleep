import java.awt.Color;

public class Editor4 {

	public static void main (String[] args) {
		String file = args[0];
		int n = Integer.parseInt(args[1]);
		Color[][] sourceImage = Runigram.read(file);
		Color[][] targetImage = Runigram.grayScaled(sourceImage);
		Runigram.setCanvas(sourceImage);
		Runigram.morph(sourceImage, targetImage, n);
	}
}
