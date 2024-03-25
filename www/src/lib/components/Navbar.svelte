<script>
    import logo from '$lib/assets/logo.png';
	import UserWidget from './UserWidget.svelte';
</script>

<!-- <div class="navbar bg-base-200 rounded-full my-5 justify-between">
    <div class="navbar-start flex-grow">
        <div class="btn btn-ghost btn-circle avatar">
            <div class="w-10 rounded-full">
                <img alt="Motmot" src={logo} />
            </div>
        </div>
        <p class="ml-1 cursor-default text-2xl font-bold select-none">Motmot</p>
    </div>

    <div class="flex-grow-0">
        <div class="navbar-middle lg:flex">
            <ul class="menu menu-horizontal px-1 mr-1">
                <li><a href="/courses" class="rounded-full font-bold">Courses</a></li>
            </ul>
        </div>
        <div class="navbar-middle lg:flex">
            <ul class="menu menu-horizontal px-1 mr-1">
                <li><a href="/mychats" class="rounded-full font-bold">My Chats</a></li>
            </ul>
        </div>
    </div>

    <div class="navbar-end flex-grow">
        <UserWidget />
    </div>
</div> -->

<div class="navbar bg-base-200 rounded-full my-5 justify-between items-center">
    <div class="navbar-start">
        <div class="btn btn-ghost btn-circle avatar">
            <div class="w-10 rounded-full">
                <img alt="Motmot" src={logo} />
            </div>
        </div>
        <p class="ml-1 cursor-default text-2xl font-bold select-none">Motmot</p>
    </div>

    <div class="flex-grow flex justify-center mx-auto">
        <div class="navbar-middle">
            <ul class="menu menu-horizontal px-1 mr-5"> <!-- Increased marginRight -->
                <li><a href="/courses" class="rounded-full font-bold">Courses</a></li>
            </ul>
        </div>

        <div class="navbar-middle">
            <ul class="menu menu-horizontal px-1 ml-5"> <!-- Increased marginLeft -->
                <li><a href="/mychats" class="rounded-full font-bold">My Chats</a></li>
            </ul>
        </div>
    </div>

    <div class="navbar-end">
        <UserWidget />
    </div>
</div>
