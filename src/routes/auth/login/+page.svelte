<title>
	Login to Which List
</title>

<h1 class="text-center font-bold text-xl">
	Login to Which List
</h1>
<form method="POST">
	<label
		for="email"
		class="block text-sm font-medium my-1"
	>
		Email
	</label>
	<input
		type="email"
		id="email"
		placeholder="Email"
		name="email"
		class="input mb-4"
	/>
	<label
		for="password"
		class="block text-sm font-medium my-1"
	>
		Password
	</label>
	<input
		type="password"
		id="password"
		placeholder="Password"
		name="password"
		class="input"
	/>
	<button
		type="submit"
		class="rounded-lg mt-4 p-2 bg-teal-600 w-full hover:bg-teal-700 duration-200"
	>
		Login
	</button>
</form>
<div class="my-4">
	<a href="/auth/register" class="anchor">Register</a>
</div>